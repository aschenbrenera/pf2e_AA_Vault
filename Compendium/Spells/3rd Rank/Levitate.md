---
tags:
  - action/spell
  - spell/rank/3
  - trait/ability/concentrate
  - trait/generic/manipulate
level: 3
format: 1_0
---
# Levitate [](#Actions "Two-Action") &emsp;*(Spell 3)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") 
**Description:** You defy gravity.

**Traditions:** arcane, occult 
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** touch
**Targets:** 1 unattended object or willing creature
**Duration:** 5 minutes
**Activity:** Two Action ⬥⬥

## Mechanical Rules

- Levitate the target 5 feet off the ground.
- You can Sustain the spell to move the target up or down 10 feet.
- A creature floating in the air from _levitate_ takes a –2 circumstance penalty to attack rolls.
	- A floating creature can spend an Interact action to stabilize itself and negate this penalty for the remainder of its turn.
- If the target is adjacent to a fixed object or terrain of suitable stability, it can move across the surface by climbing (if the surface is vertical, like a wall) or crawling (if the surface is horizontal, such as a ceiling). The GM determines which surfaces can be climbed or crawled across.