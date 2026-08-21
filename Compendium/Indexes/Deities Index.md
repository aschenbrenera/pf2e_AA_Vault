---
tags:
  - index
format: 2.0
source: Player Core
---

# Deities Index

```dataview  
TABLE WITHOUT ID link(file.name) AS "Deity", sanctification AS "Sanctification", attributes AS "Divine Attributes", skill AS "Divine Skill", domains AS "Domains"
FROM "Compendium/Deities"
SORT file.name
```

# Deities by Domain

```dataviewjs
const pages = dv.pages('"Compendium/Deities"');

const domains = [...new Set(
    pages.flatMap(p => Array.isArray(p.domains) ? p.domains : [p.domains])
        .filter(Boolean)
        .map(String)
)].sort();

const label = dv.container.createEl("label", { text: "Domain: " });
const select = label.createEl("select");
domains.forEach(d => select.createEl("option", { text: d, value: d }));

const output = dv.container.createDiv();

function render() {
    output.empty();

    const domain = select.value.toLowerCase();

    const results = pages
        .where(p => {
            const d = Array.isArray(p.domains) ? p.domains : [p.domains];
            return d.some(x => String(x).toLowerCase() === domain);
        })
        .sort(p => p.file.name);

    const oldContainer = dv.container;
    dv.container = output;

    dv.table(
        ["Deity", "Sanctification", "Divine Attributes", "Divine Skill", "Domains"],
        results.map(p => [
            p.file.link,
            p.sanctification,
            p.attributes,
            p.skill,
            p.domains
        ])
    );

    dv.container = oldContainer;
}

select.addEventListener("change", render);
render();
```