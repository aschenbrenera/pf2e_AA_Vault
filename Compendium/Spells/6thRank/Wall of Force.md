---
tags:
  - action/spell
  - spell/rank/6
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/force
level: 6
format: 1_0
---
# Wall of Force [](#Actions "Three-Action") &emsp;*(Spell 6)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Force](Force.md "Effect Trait") 
**Description:** 

**Traditions:** arcane, occult   
**Catalysts:** [Force Tiles](https://2e.aonprd.com/Equipment.aspx?ID=1006), [Force Tiles](https://2e.aonprd.com/Equipment.aspx?ID=5052)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 30 feet
**Duration:** 1 minute
**Activity:** Three Actions ⬥⬥⬥

## Mechanical Rules

- You form an invisible wall of pure magical force up to 50 feet long and up to 20 feet high.
	- The wall has no discernible thickness.
	- The wall has AC 10, Hardness 30, and 60 Hit Points, and it's immune to critical hits and precision damage.
- You must create the wall in an unbroken open space so its edges don't pass through any creatures or objects, or the spell is lost. 
- The wall blocks physical effects from passing through it, and because it's made of force, it blocks `Incorporeal` and `Ethereal` creatures as well. 
- `Teleportation` effects can pass through the barrier, as can `Visual` effects (since the wall is invisible).  
- _Wall of force_ is immune to effects of its rank or lower that attempt to [[Counteracting|Counteract]] it.
- The wall is automatically destroyed by a [[Disintegrate]] spell of any rank.

> [!info] Heighten
>- **Heightened (+2):** The Hit Points of the wall increases by 20.