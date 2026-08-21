---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/effect/fortune
level: 1
format: 1_0
---
# Sure Strike [](#Actions "Single Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Fortune](Manipulate.md "Effect Trait") 
**Description:** Improve the accuracy of your next attack.

**Traditions:** arcane, occult 
**Mystery:** battle  
**Patron Theme:** spinner of threads
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Duration:** Until the end of your turn
**Activity:** One Action ⬥

## Mechanical Rules

- The next time you make an attack roll before the end of your turn, roll it twice and use the better result.
	- The attack ignores circumstance penalties to the attack roll and any flat check required due to the target being [[Concealed]] or [[Hidden]].
	- You are then temporarily immune to sure strike for 10 minutes.