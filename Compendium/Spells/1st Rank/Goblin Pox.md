---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/disease
level: 1
format: 1_0
---
# Goblin Pox [](#Actions "Two-Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Disease](Disease.md "Effect Trait") 
**Description:** Your touch gives an irritating allergenic rash.

**Traditions:** arcane, primal
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** touch
**Targets:** 1 creature
**Defense:** Fortitude
**Cast:** Two Action ⬥⬥

## Mechanical Rules

	- Your touch afflicts the target with goblin pox. The target must attempt a Fortitude save.
  > [!success-degree]
  > - **Critical Success**: The target is unaffected.
  > - **Success**: The target is [[Sickened]] 1.
  > - **Failure:** The target is afflicted with goblin pox at stage 1.
  > - **Critical Failure**: The target is afflicted with goblin pox at stage 2.

- **Goblin Pox** ([Disease](Disease.md "Effect Trait"))  &emsp;*(Level 1)* 
	- Creatures that have the [Goblin](Compendium/Ancestries/Common/Monstrous/Goblin.md "Ancestry & Heritage Trait") trait and [Goblin Dogs](https://2e.aonprd.com/Monsters.aspx?ID=236) are immune.
	 - **Stage 1:** sickened 1 (1 round)
	 - **Stage 2:** sickened 1 and [[Slowed]] 1 (1 round)
	 - **Stage 3:** sickened 1 and the creature can't reduce its sickened value below 1 (1 day)