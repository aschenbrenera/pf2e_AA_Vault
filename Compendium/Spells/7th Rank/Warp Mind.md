---
tags:
  - action/spell
  - spell/rank/7
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/incapacitation
  - trait/effect/emotion
  - trait/effect/mental
level: 7
format: 1_0
---
# Warp Mind [](#Actions "Two-Action") &emsp;*(Spell 7)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Incapacitation](Incapacitation.md "Effect Trait") [Mental](Mental.md "Effect Trait") [Emotion](Rules/Traits/Effect/Emotion.md "Effect Trait")
**Description:** You scramble a creature's mental faculties and sensory input.

**Traditions:** arcane, occult, primal 
**Bloodline:** aberrant, hag
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Targets:** 1 creature
**Defense:** Will
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- The target must attempt a Will saving throw. 
	- Regardless of the result of that save, the target is then temporarily immune for 10 minutes.
  > [!success-degree]
  > **Critical Success:** The target is unaffected.
  > **Success:** The target spends the first action on its next turn with the [[Confused]] condition.
  > **Failure:** The target is confused for 1 minute.
  > **Critical Failure:** The target is confused permanently.


## Gameplay Interaction

- Follows the rules for the `Incapacitation` trait.
	- If the incapacitation trait is on a spell, a creature with a level of more than twice the spell's effective rank gains the listed benefit against the spell (Heightened Spells increase a spell's effective rank).
	- **Benefit:** Creatures with this benefit treat the result of their check to prevent being incapacitated as one degree of success better or the result of any check the spellcaster made to incapacitate them as one degree of success worse.
- Follows the rules for the `Emotion` and `Mental` traits.
    - Creatures with special training or that have mechanical or artificial intelligence are immune to emotion effects.
    - Mental effects have no effect on an object or a `Mindless` creature.