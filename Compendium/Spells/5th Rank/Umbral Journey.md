---
tags:
  - action/spell
  - spell/rank/5
  - trait/rarity/uncommon
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/shadow
  - trait/effect/teleportation
level: 5
format: 1_0
---
# Umbral Journey &emsp;*(Spell 5)*

  [Uncommon](Uncommon.md "Uncommon Rarity Trait") [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Shadow](Rules/Traits/Effect/Shadow.md "Effect Trait")  [Teleportation](Teleportation.md "Effect Trait") 
**Description:** You move partially into the Netherworld, using its warped nature to speed your travels.

**Traditions:** arcane, occult
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** touch
**Targets:** you and up to 10 willing creatures touched
**Duration:** 8 hours
**Cast:** 10 minutes

## Mechanical Rules

- Each hour, you cover roughly as much ground as you normally would in 3 days of [[Travel speed]].
- The landmarks are vague and symbolic rather than concrete, leaving you within a mile of your intended destination when you Dismiss the spell or its duration ends.