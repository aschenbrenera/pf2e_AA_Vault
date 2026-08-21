---
tags:
  - action/spell
  - spell/rank/8
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/extradimensional
  - trait/effect/teleportation
level: 8
format: 1_0
---
# Quandary [](#Actions "Two-Action") &emsp;*(Spell 8)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Extradimensional](Extradimensional.md "Effect Trait") [Teleportation](Teleportation.md "Effect Trait") 
**Description:** You transport the target into an extraplanar puzzle room of mysterious origin, locking them there.

**Traditions:** arcane, occult  
**Bloodline** hag, imperial
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 30 feet
**Targets:** 1 creature  
**Duration:** sustained
**Cast:** Two Actions ⬥⬥

## Mechanical Rules

- Transport the target into an extraplanar puzzle room.
	- Once each turn as a single action, the target can attempt an Occultism check, Perception check, or Thievery check against your spell DC to solve the puzzle.
  > [!success-degree]
  > **Critical Success:** The target solves the puzzle and escapes.
  > **Success:** The target is on the right path to the solution. If it was already on the right path, it solves the puzzle and escapes.
  > **Failure:** The target makes no progress toward a solution.
  > **Critical Failure:** The target makes no progress and, if it was on the right path, it no longer is.
	- `Teleportation` effects can't carry the target outside the puzzle room unless they can also traverse the planes, such as [[Interplanar Teleport]]. 
	- When the spell ends, the target returns to the space it occupied when it was banished, or to the nearest space if the original is now filled.
