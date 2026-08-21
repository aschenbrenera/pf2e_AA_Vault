---
tags:
  - action/spell
  - spell/rank/5
  - trait/ability/concentrate
  - trait/generic/manipulate
level: 5
format: 1_0
---
# Telekinetic Haul [](#Actions "Two-Action")  &emsp;*(Spell 5)*

[Concentrate](Concentrate.md "General Trait") [Manipulate](Manipulate.md "General Trait")
**Description:** 

**Traditions:** arcane, occult 
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Targets:** 1 unattended object of up to 80 Bulk with no dimension longer than 20 feet
**Duration:** sustained up to 1 minute
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You move the target up to 20 feet, potentially suspending it in midair.
- When you Sustain the spell, you can do so again, or you can shift your telekinetic focus to a different eligible target within range, moving it instead.