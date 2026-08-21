---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/mental
level: 1
format: 1_0
---
# Mindlink [](#Actions "Two-Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Mental](Mental.md "Effect Trait")
**Description:** You link your mind to the target's mind.

**Traditions:** arcane, occult 
**Mystery:** lore
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** Touch
**Targets:** 1 willing creature
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You mentally impart to that target an amount of information in an instant that could otherwise be communicated in 10 minutes.