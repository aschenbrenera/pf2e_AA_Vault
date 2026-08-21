---
tags:
  - action/spell
  - spell/rank/5
  - trait/generic/manipulate
  - trait/effect/incapacitation
  - trait/effect/illusion
  - trait/effect/mental
  - trait/spell/subtle
level: 5
format: 1_0
---
# Hallucination [](#Actions "Two-Action") &emsp;*(Spell 5)*

[Manipulate](Manipulate.md "General Trait") [Incapacitation](Incapacitation.md "Effect Trait") [Illusion](Illusion.md "Effect Trait") [Mental](Mental.md "Effect Trait") [Subtle](Subtle.md "Spell Trait")
**Description:** The target hallucinates.

**Traditions:** arcane, occult 
**Bloodline:** fey
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 30 feet
**Targets:** 1 creature
**Duration:** 1 hour
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- The target consistently detects one thing as another, can't detect something that's there, or detects something that's not there, though it doesn't alter their beliefs. You choose which of these effects applies, and you determine the specifics of the hallucination. 
	- For example, you could make the target see all elves as humans, be unable to detect the presence of their brother, see their beloved good luck charm on their person even when it isn't, or see a tower in the center of town.  
- The target can attempt an initial Will save, with effects below. They also receive a Will save to disbelieve the hallucination every time they Seek or directly interact with the hallucination.
	- For example, the target could attempt to disbelieve the hallucination each time they interacted with an elf, bumped into their brother accidentally, tried to check their charm, or studied the tower. The target can attempt to disbelieve with a large circumstance bonus in situations determined by the GM, such as if the target attempted to climb the nonexistent tower.
  > [!success-degree]
  > **Critical Success:** The creature is unaffected.
  > **Success:** The creature perceives what you chose until it disbelieves, but it knows what the hallucination is.
  > **Failure:** The creature perceives what you chose until it disbelieves.
  > **Critical Failure:** The creature perceives what you chose until it disbelieves, and it trusts its false senses, taking a –4 circumstance penalty to saves to disbelieve.

> [!info] Heighten
>- **Heightened (6th):** Choose to either target up to 10 creatures or change the spell's duration to until your next daily preparations.
>- **Heightened (8th):** Choose to either target any number of creatures or change the spell's duration to unlimited.

## Gameplay Interaction

- Follows the rules for the [[Incapacitation]] trait.
	- If the incapacitation trait is on a spell, a creature with a level of more than twice the spell's effective rank gains the listed benefit against the spell (Heightened Spells increase a spell's effective rank).
	- **Benefit:** Creatures with this benefit treat the result of their check to prevent being incapacitated as one degree of success better or the result of any check the spellcaster made to incapacitate them as one degree of success worse.
- Follows the rules for the [[Subtle]] trait.
	- A spell with the subtle trait can be cast without incantations and doesn't have obvious manifestations.