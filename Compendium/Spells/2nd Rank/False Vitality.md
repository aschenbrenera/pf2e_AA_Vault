---
tags:
  - action/spell
  - spell/rank/2
  - trait/ability/concentrate
  - trait/generic/manipulate
level: 2
format: 1_0
---
# False Vitality  [](#Actions "Two-Action") &emsp;*(Spell 2)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") 
**Description:** You augment your flesh with the energies typically used to manipulate the undead.

**Traditions:** arcane, occult
**Mysteries:** bones, life
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Duration:** 8 hours
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You gain 10 temporary Hit Points.

> [!info] Heighten
>- **Heightened (+1):** The temporary Hit Points increase by 3.