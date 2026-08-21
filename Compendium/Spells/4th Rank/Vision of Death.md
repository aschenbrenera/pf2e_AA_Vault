---
tags:
  - action/spell
  - spell/rank/4
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/death
  - trait/effect/emotion
  - trait/effect/fear
  - trait/effect/mental
level: 4
format: 1_0
---
# Vision of Death [](#Actions "Two-Action") &emsp;*(Spell 4)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Death](Death.md "Effect Trait") [Emotion](Rules/Traits/Effect/Emotion.md "Effect Trait") [Fear](Fear.md "Effect Trait") [Mental](Mental.md "Effect Trait")
**Description:** You force the target to see a vision of its own death.

**Traditions:** arcane, occult 
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Targets:** 1 living creature
**Defense:** Will
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- Target takes 8d6 mental damage with a Will save. 
  > [!success-degree]
  > **Critical Success:** The target is unaffected.
  > **Success:** The target takes half damage and is [[Frightened]] 1.
  > **Failure:** The target takes full damage and is Frightened 2.
  > **Critical Failure:** The target takes double damage, is frightened 4, and is [[Fleeing]] for as long as it's frightened.
- If the target is reduced to 0 HP by this spell, its vision becomes reality and kills it instantly.

## Gameplay Interaction

- Follows the rules for the `Emotion` and `Mental` traits.
    - Creatures with special training or that have mechanical or artificial intelligence are immune to emotion effects.
    - Mental effects have no effect on an object or a `Mindless` creature.