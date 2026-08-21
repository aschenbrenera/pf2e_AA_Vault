---
tags:
  - action/spell
  - spell/rank/1
  - trait/generic/manipulate
  - trait/generic/move
level: 1
format: 1_0
---
# Jump [](#Actions "Single Action") &emsp;*(Spell 1)*

[Manipulate](Manipulate.md "General Trait") [Move](Move.md "General Trait")
**Description:** Your legs surge with strength, ready to leap high and far.

**Traditions:** arcane, primal
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Cast:** One Action ⬥

## Mechanical Rules

- You jump 30 feet in any direction without touching the ground.
	- You must land on a space of solid ground within 30 feet of you, or else you fall after using your next action.

> [!info] Heighten
>- **Heightened (3rd):** The range becomes touch, the target changes to one touched creature, and the duration becomes 1 minute, allowing the target to jump as described whenever it takes the [[Leap]] action.