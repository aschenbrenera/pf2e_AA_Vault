---
tags:
  - action/spell
  - spell/rank/3
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/plant
  - trait/effect/wood
level: 3
format: 1_0
---
# Wall of Thorns [](#Actions "Three-Action") &emsp;*(Spell 3)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Plant](Plant.md "Effect Trait") [Wood](Wood.md "Effect Trait") 
**Description:** You grow a wall of thorny brambles from the ground.

**Traditions:** arcane, primal   
**Catalysts:** [Black Ash](https://2e.aonprd.com/Equipment.aspx?ID=3746)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 60 feet
**Duration:** 1 minute
**Activity:** Three Actions ⬥⬥⬥

## Mechanical Rules

- You create a 5-foot-thick wall of brambles and thorns in a straight line up to 60 feet long and 10 feet high.
	- You must create the wall in an unbroken open space so its edges don't pass through any creatures or objects, or the spell is lost.
	- The wall stands vertically. If you wish, the wall can be of a shorter length or height.
	- Each 10-foot-by-10-foot section of the wall has AC 10, Hardness 10, and 20 Hit Points. It's immune to critical hits and precision damage.
	- A destroyed section can be moved through freely.
- Everything on each side of the wall has cover from creatures on the opposite side, and the wall's spaces are difficult terrain.
- For every move action a creature uses to enter at least one of the wall's spaces, that creature takes 3d4 piercing damage.  

> [!info] Heighten
>- **Heightened (+1):** The Hit Points of each section of the wall increase by 5, and the piercing damage increases by 1d4.