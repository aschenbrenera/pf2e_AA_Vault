---
tags:
  - action/spell
  - spell/rank/3
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/earth
level: 3
format: 1_0
---
# Earthbind [](#Actions "Two-Action") &emsp;*(Spell 3)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Earth](Earth.md "Effect Trait") 
**Description:** Using the weight of earth, you hamper a target's flight.

**Traditions:** arcane, primal 
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Targets:** 1 flying creature
**Defense:** Fortitude
**Duration:** Varies
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- The target makes a Fortitude save.
  > [!success-degree]
  > - **Critical Success**: The target is unaffected.
  > - **Success**: The target falls safely up to 120 feet.
  > - **Failure:** The target falls safely up to 120 feet. If it hits the ground, it can't [[Fly]], Levitate, or otherwise leave the ground for 1 round.
  > - **Critical Failure**: The target falls safely up to 120 feet. If it hits the ground, it can't Fly, _levitate_, or otherwise leave the ground for 1 minute.
 - If the creature reaches the ground safely, it doesn't take [[Falling|Falling Damage]].