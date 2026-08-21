---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/poison
level: 1
format: 1_0
---
# Spider Sting [](#Actions "Two-Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Poison](Poison.md "Effect Trait") 
**Description:** You magically duplicate a spider's venomous sting.

**Traditions:** arcane, primal   
**Catalysts:** [Ogre Spider Filament](https://2e.aonprd.com/Equipment.aspx?ID=3262)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** touch
**Targets:** 1 creature
**Defense:** Fortitude
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You deal 1d4 piercing damage to the touched creature and afflict it with spider venom. The target must attempt a Fortitude save.
  > [!success-degree]
  > - **Critical Success**: The target is unaffected.
  > - **Success**: The target takes 1d4 poison damage.
  > - **Failure:** The target is afflicted with spider venom at stage 1.
  > - **Critical Failure**: The target is afflicted with spider venom at stage 2. 
 - **Spider Venom** ([Poison](Poison.md "Effect Trait"))  &emsp;*(Level 1)* 
	 - **Maximum Duration:** 4 rounds
	 - **Stage 1:** 1d4 poison damage and [[Enfeebled]] 1 (1 round)
	 - **Stage 2:** 1d4 poison damage and Enfeebled 2 (1 round)