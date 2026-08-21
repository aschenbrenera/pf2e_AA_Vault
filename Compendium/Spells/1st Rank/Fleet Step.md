---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/generic/manipulate
level: 1
format: 1_0
---
# Fleet Step [](#Actions "Two-Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") 
**Description:** You gain a burst of speed.

**Traditions:** arcane, primal
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Duration:** 1 minute
**Activity:** Two Action ⬥⬥

## Mechanical Rules

- You gain a +30-foot status bonus to your Speed.