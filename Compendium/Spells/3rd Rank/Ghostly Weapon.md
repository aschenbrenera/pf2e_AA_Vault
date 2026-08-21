---
tags:
  - action/spell
  - spell/rank/3
  - trait/ability/concentrate
  - trait/generic/manipulate
level: 3
format: 1_0
---
# Ghostly Weapon [](#Actions "Two-Action") &emsp;*(Spell 3)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") 
**Description:** The target weapon becomes translucent and ghostly.

**Traditions:** arcane, occult 
**Mystery:** bones
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** touch
**Targets:** 1 weapon that is either unattended or wielded by you or a willing ally
**Duration:** 5 minutes
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- The target can affect material and [[Incorporeal]] creatures and objects.
- It gains the effects of the [[Ghost Touch Rune|Ghost Touch]] property rune, meaning it is `Magical` if it wasn't already, is especially effective against incorporeal creatures, and can be wielded by a corporeal or incorporeal creature.