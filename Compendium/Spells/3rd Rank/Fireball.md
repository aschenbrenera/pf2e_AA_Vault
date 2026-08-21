---
tags:
  - action/spell
  - spell/rank/3
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/fire
level: 3
format: 1_0
---
# Fireball [](#Actions "Two-Action") &emsp;*(Spell 3)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Fire](Fire.md "Effect Trait") 
**Description:** A roaring blast of fire detonates at a spot you designate.

**Traditions:** arcane, primal   
**Catalysts:** [Firestarter Pellets](https://2e.aonprd.com/Equipment.aspx?ID=1005)
**Mystery:** flames
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 500 feet
**Area:** 20-foot burst
**Defense:** [[Basic Saving Throw|Basic]] Reflex
**Activity:** Two Actions ⬥⬥

## Mechanical Rules

- Deals 6d6 fire damage in the area.

> [!info] Heighten
>- **Heightened (+1):** The damage increases by 2d6.