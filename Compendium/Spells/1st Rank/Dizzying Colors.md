---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/incapacitation
  - trait/effect/illusion
  - trait/effect/visual
level: 1
format: 1_0
---
# Dizzying Colors [](#Actions "Two-Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Incapacitation](Incapacitation.md "Effect Trait") [Illusion](Illusion.md "Effect Trait") [Visual](Rules/Traits/Effect/Visual.md "Effect Trait")
**Description:** You unleash a swirling multitude of colors that overwhelms creatures.

**Traditions:** arcane, occult, primal 
**Catalysts:** [Seventh Prism](https://2e.aonprd.com/Equipment.aspx?ID=2028)
**Mystery:** cosmos
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Area:** 15-foot cone
**Defense:** Will
**Duration:** 1 or more rounds (see below)
**Activity:** Two Action ⬥⬥

## Mechanical Rules

- Creatures in the area make a Will save.
  > [!success-degree]
  > **Critical Success** The creature is unaffected.
  > **Success** The creature is [[Dazzled]] for 1 round.
  > **Failure** The creature is [[Stunned]] 1, [[Blinded]] for 1 round, and Dazzled for 1 minute.
  > **Critical Failure** The creature is Stunned for 1 round and Blinded for 1 minute.

## Gameplay Interaction

- Follows the rules for the `Incapacitation` trait.
	- If the incapacitation trait is on a spell, a creature with a level of more than twice the spell's effective rank gains the listed benefit against the spell (Heightened Spells increase a spell's effective rank).
	- **Benefit:** Creatures with this benefit treat the result of their check to prevent being incapacitated as one degree of success better or the result of any check the spellcaster made to incapacitate them as one degree of success worse.
- Follows the rules for the `Visual` trait.
    - A visual effect can affect only creatures that can see it.