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
# Fire Shield [](#Actions "Two-Action") &emsp;*(Spell 4)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Fire](Rules/Traits/Effect/Fire.md "Effect Trait") 
**Description:** You create a hovering shield made of fire.

**Traditions:** arcane, primal   
**Catalysts:** [Nevercold](https://2e.aonprd.com/Equipment.aspx?ID=2026), [Witchwarg Fur](https://2e.aonprd.com/Equipment.aspx?ID=3266)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Duration:** 1 minute
**Activity:** Two Actions ⬥⬥

## Mechanical Rules

- The shield's heat grants you cold resistance 5 and makes you immune to [[Temperature]] damage from mild and severe cold.
- You can [[Raise a Shield]] with the fire shield as a normal shield to gain a +1 circumstance bonus to AC.
	- You can use the [[Shield Block]] reaction with the fire shield, which has Hardness 10, is immune to fire, and has 40 HP (with no Broken Threshold), and its Hardness is halved against effects that have the Water trait. 
	- If you Shield Block a melee attack that is either an unarmed attack or made by an adjacent attacker, the attacker takes 2d6 fire damage.

> [!info] Heighten
>- **Heightened (+2):** The cold resistance increases by 5, the HP increase by 10, and the fire damage increases by 1d6.