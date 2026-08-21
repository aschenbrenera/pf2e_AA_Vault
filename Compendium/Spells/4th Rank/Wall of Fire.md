---
tags:
  - action/spell
  - spell/rank/4
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/fire
level: 4
format: 1_0
---
# Wall of Fire [](#Actions "Three-Action") &emsp;*(Spell 4)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Fire](Rules/Traits/Effect/Fire.md "Effect Trait") 
**Description:** You raise a blazing wall that burns creatures passing through it.

**Traditions:** arcane, primal   
**Catalysts:** [Noxious Incense](https://2e.aonprd.com/Equipment.aspx?ID=5060)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Duration:** 1 minute
**Activity:** Three Actions ⬥⬥⬥

## Mechanical Rules

- You create a vertical wall in one of the following forms:
	- a 5-foot-thick wall of flame in a straight line up to 60 feet long and 10 feet high
	- a 5-foot-thick, 10-foot-radius ring of flame 10 feet high
- If you wish, the wall can be of a shorter length or height.
- Everything on each side of the wall is [[Concealed]] from creatures on the opposite side.
- Any creature that crosses the wall or is occupying the wall's area at the start of its turn takes 4d6 fire damage.

> [!info] Heighten
>- **Heightened (+1):** The fire damage increases by 1d6.