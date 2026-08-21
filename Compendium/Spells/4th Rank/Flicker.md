---
tags:
  - action/spell
  - spell/rank/4
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/teleportation
level: 4
format: 1_0
---
# Flicker [](#Actions "Two-Action") &emsp;*(Spell 4)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Teleportation](Teleportation.md "Effect Trait") 
**Description:** You flicker quickly between your current plane and another.

**Traditions:** arcane, occult  
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Duration:** 1 minute
**Cast:** Two Actions ⬥⬥

## Mechanical Rules

- You gain resistance 5 to all damage, except force.
- At the end of each of your turns, you automatically teleport 10 feet in a random direction, as determined by the GM.
- You can Sustain the spell to teleport in this way.
  
> [!info] Heighten
>- **Heightened (+2):** The resistance increases by 3.