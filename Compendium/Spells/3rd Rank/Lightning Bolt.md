---
tags:
  - action/spell
  - spell/rank/3
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/electricity
  - defense/reflex
level: 3
format: 1_0
---
# Lightning Bolt [](#Actions "Two-Action") &emsp;*(Spell 3)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Electricity](Rules/Traits/Effect/Electricity.md "Effect Trait") 
**Description:** A bolt of lightning strikes outward from your hand.

**Traditions:** arcane, primal 
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Area:** 120-foot line
**Defense:** [[Basic Saving Throw|Basic]] Reflex
**Activity:** Two Actions ⬥⬥

## Mechanical Rules

- Deals 4d12 electricity damage with a basic Reflex save.

> [!info] Heighten
>- **Heightened (+1):** The damage increases by 1d12.