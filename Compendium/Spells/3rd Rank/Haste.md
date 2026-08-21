---
tags:
  - action/spell
  - spell/rank/3
  - trait/ability/concentrate
  - trait/generic/manipulate
level: 3
format: 1_0
---
# Haste [](#Actions "Two-Action") &emsp;*(Spell 3)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") 
**Description:** Magic empowers the target to act faster. 

**Traditions:** arcane, occult, primal 
**Bloodline:** draconic, imperial
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 30 feet
**Targets:** 1 creature
**Duration:** 1 minute
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- Target gains the [[Quickened]] condition and can use the extra action each round for only Strike and Stride actions.
  
> [!info] Heighten
>- **Heightened (7th):** You can target up to 6 creatures.