---
tags:
  - action/spell
  - spell/rank/2
  - trait/generic/manipulate
  - trait/effect/illusion
  - trait/spell/subtle
level: 1
format: 1_0
---
# Invisibility [](#Actions "Two-Action") &emsp;*(Spell 2)*

[Manipulate](Manipulate.md "General Trait") [Illusion](Illusion.md "Effect Trait") [Subtle](Subtle.md "Spell Trait")
**Description:** Illusions bend light around the target, rendering it Invisible.

**Traditions:** arcane, occult
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** Touch
**Targets:** 1 creature
**Duration:** 10 minutes
**Activity:** Two Action ⬥⬥

## Mechanical Rules

- The target becomes [[Invisible]]. This makes it Undetected to all creatures, though the creatures can attempt to find the target, making it Hidden to them instead. If the target uses a [[Hostile]] action, the spell ends after that hostile action is completed.

> [!info] Heighten
>- **Heightened (4th):** The spell lasts 1 minute, but it doesn't end if the target uses a hostile action.

## Gameplay Interaction

- Follows the rules for the [[Subtle]] trait.
	- A spell with the subtle trait can be cast without incantations and doesn't have obvious manifestations.