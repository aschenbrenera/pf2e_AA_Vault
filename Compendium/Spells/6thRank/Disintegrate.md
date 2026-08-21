---
tags:
  - action/spell
  - spell/rank/6
  - trait/combat/attack
  - trait/ability/concentrate
  - trait/generic/manipulate
level: 6
format: 1_0
---
# Disintegrate [](#Actions "Two-Action") &emsp;*(Spell 6)*

[Attack](Attack.md "General Trait") [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait")
**Description:** 

**Traditions:** arcane
**Bloodlines:** demonic, imperial
**Mystery:** ash
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Targets:** 1 creature, unattended object, or force construct
**Defense:** AC and [[Basic Saving Throw|Basic]] Fortitude
**Cast:** Two Actions ⬥⬥

## Mechanical Rules

- A black tracer bolt flies toward your target, and upon making contact intensifies into a powerful destructive beam.
- Make a spell attack against the target.
	- If you hit an object or force construct (such as a [[Wall of Force]]), it's destroyed with no save unless it's an [[Artifact]] or similarly powerful. 
		- A single casting can destroy no more than a 10-foot cube of matter.  
	- If you hit a creature, it takes 12d10 damage (no damage type) with a basic Fortitude save. 
	- If you critically hit a creature, the target gets a result one degree of success worse than the outcome of its Fortitude save.
	- A creature reduced to 0 HP is blasted to fine powder; its gear remains.

> [!info] Heighten
>- **Heightened (+1):** The damage increases by 2d10.