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
# Translocate [](#Actions "Two-Action") &emsp;*(Spell 4)*

 [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Teleportation](Teleportation.md "Effect Trait") 
**Description:** Teleport to somewhere else.

**Traditions:** arcane, occult  
**Bloodline** imperial
**Catalysts** [Dimensional Knot](https://2e.aonprd.com/Equipment.aspx?ID=5048)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Activity:** Two Actions ⬥⬥

## Mechanical Rules

- You instantly transport yourself and any items you're wearing and holding from your current space to an unoccupied space within range you can see. 
- If this would bring another creature with you—even if you're carrying it in an extradimensional container—the spell is lost.

> [!info] Heighten
>- **Heightened (5th):** The range increases to 1 mile. You don't need to be able to see your destination, as long as you have been there in the past and know its relative location and distance from you. You are then temporarily immune for 1 hour.