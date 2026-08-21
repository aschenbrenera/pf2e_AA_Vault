---
tags:
  - action/spell
  - spell/rank/2
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/polymorph
level: 2
format: 1_0
---
# Enlarge  [](#Actions "Two-Action") &emsp;*(Spell 2)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Polymorph](Polymorph.md "Effect Trait")
**Description:** Bolstered by magical power, the target grows.

**Traditions:** arcane, primal 
**Bloodline:** demonic
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 30 feet
**Targets:** 1 willing creature
**Duration:** 5 minutes
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- The target grows to size Large.
	- Its equipment grows with it but returns to natural size if removed. The creature is [[Clumsy]] 1.
	- Its [[Rules/General/Reach|Reach]] increases by 5 feet (or by 10 feet if it started out Tiny), and it gains a +2 status bonus to damage rolls on melee Strikes.
- This spell has no effect on a Large or larger creature.

> [!info] Heighten
>- **Heightened (4th):** The creature instead grows to size Huge. The status bonus to melee damage is +4 and the creature's reach increases by 10 feet (or 15 feet if the creature started out Tiny). The spell has no effect on a Huge or larger creature.
>- **Heightened (6th):** Choose either the 2nd-rank or 4th-rank version of this spell and apply its effects to up to 10 willing creatures.