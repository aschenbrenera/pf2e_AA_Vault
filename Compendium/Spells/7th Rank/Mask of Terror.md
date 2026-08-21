---
tags:
  - action/spell
  - spell/rank/7
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/emotion
  - trait/effect/fear
  - trait/effect/illusion
  - trait/effect/mental
  - trait/effect/visual
level: 7
format: 1_0
---
# Mask of Terror [](#Actions "Two-Action") &emsp;*(Spell 7)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Emotion](Emotion.md "Effect Trait") [Fear](Fear.md "Effect Trait") [Illusion](Illusion.md "Effect Trait") [Mental](Mental.md "Effect Trait") [Visual](Visual.md "Effect Trait")
**Description:** The target appears to be a gruesome and terrifying creature.  The effect is unique to each observer, so a human viewing the target might see a demon with bloody fangs, but a demon observing the target might see a glowing angelic visage.  

**Traditions:** arcane, occult, primal
**Bloodline:** draconic   
**Catalysts:** [Defiled Costa](https://2e.aonprd.com/Equipment.aspx?ID=1793)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 30 feet
**Targets:** 1 creature
**Duration:** 1 minute
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- When any creature attempts a [[Hostile]] action against the target, the creature must attempt a Will save. It is then temporarily immune until the end of its next turn.
  > [!success-degree]
  > **Success:** The creature is unaffected.
  > **Failure:** The creature becomes [[Frightened]] 2 before using its action.
  > **Critical Failure:** The creature becomes frightened 2, and its action fails and is wasted.

> [!info] Heighten
>- **Heightened (8th):** You can target up to 5 creatures. If a creature uses a hostile action or reaction that affects multiple targets simultaneously, it needs to attempt only one save against _mask of terror_.

## Gameplay Interaction

- Follows the rules for the `Emotion`, `Mental`, and `Visual` traits.
    - Creatures with special training or that have mechanical or artificial intelligence are immune to emotion effects.
    - Mental effects have no effect on an object or a `Mindless` creature.
    - A visual effect can affect only creatures that can see it.