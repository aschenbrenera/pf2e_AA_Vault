---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/illusion
  - trait/effect/mental
  - trait/item/weapon_trait/nonlethal
level: 1
format: 1_0
---
# Phantom Pain [](#Actions "Two-Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Illusion](Illusion.md "Effect Trait") [Mental](Mental.md "Effect Trait") [Nonlethal](Nonlethal.md "Effect Trait")
**Description:** Illusory pain wracks the target.

**Traditions:** occult 
**Bloodline:** aberrant
**Lesson:** [lesson of vengeance](https://2e.aonprd.com/Lessons.aspx?ID=20)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 30 feet
**Targets:** 1 creature
**Defense:** Will
**Duration:** 1 minute
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- The target takes 2d4 mental damage and 1d4 [[Persistent Damage|Persistent]] mental damage with a Will save.
  > [!success-degree]
  > **Critical Success** The target is unaffected.
  > **Success** The target takes full initial damage but no persistent damage, and the spell ends immediately.
  > **Failure** The target takes full initial and persistent damage, and the target is [[Sickened]] 1. If the target recovers from being sickened, the persistent damage ends and the spell ends.
  > **Critical Failure** As failure, but the target is sickened 2.

> [!info] Heighten
>- **Heightened (+1):** The damage increases by 2d4 and the persistent damage by 1d4.

## Gameplay Interaction

- Follows the rules for the `Mental` trait.
    - Mental effects have no effect on an object or a `Mindless` creature.
- Follows the rules for the `Nonlethal` trait.
    - When reduced to 0 Hit Points, if the damage was dealt by a nonlethal attack or nonlethal effect, a creature is knocked out with the following effects:
        - Move initiative position to directly before the current turn.
        - Gain Unconscious condition with 0 Hit Points.