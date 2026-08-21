---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/fire
level: 1
format: 1_0
---
# Breathe Fire [](#Actions "Two-Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Fire](Fire.md "Effect Trait") 
**Description:** A gout of flame sprays from your mouth.

**Traditions:** arcane, primal   
**Catalysts:** [Dragon Breath Scale](https://2e.aonprd.com/Equipment.aspx?ID=2022), [Dragon Eye](https://2e.aonprd.com/Equipment.aspx?ID=4014)
**Mystery:** flames, ash
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Area:** 15-foot cone
**Defense:** [[Basic Saving Throw|Basic]] Reflex
**Activity:** Two Action ⬥⬥

## Mechanical Rules

- You deal 2d6 fire damage to creatures in the area with a basic Reflex save.

> [!info] Heighten
>- **Heightened (+1):** The damage increases by 2d6.