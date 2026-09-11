---
tags:
  - action/spell
  - spell/rank/2
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/polymorph
level: 2
format: 1_0
---
# Humanoid Form  [](#Actions "Two-Action") &emsp;*(Spell 2)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Polymorph](Polymorph.md "Effect Trait")
**Description:** You transform your appearance to that of a humanoid.

**Traditions:** arcane, occult, primal 
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Duration:** 10 minutes
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You transform your appearance to that of a Small or Medium humanoid, such as a dwarf, elf, goblin, halfling, human, or orc. 
	- You gain the [[Humanoid]] trait in addition to your other traits while in this form, as well as any trait related to the creature's kind (such as `Goblin` or `Human`). 
	- You can still wear and use your gear, which changes size (if necessary) to match your new form. If items leave your person, they return to their usual size.  
	- This transformation doesn't change your statistics in any way, and you don't gain any special abilities of the humanoid form you assume. 
	- If this transformation reduces your size, it reduces your reach accordingly (typically to 5 feet). 
	- Grants you a +4 status bonus to Deception checks to pass as a generic member of the chosen ancestry, and you add your level even if you're untrained, but you can't make yourself look like a specific person.
		- If you want to Impersonate an individual, you still need to create a disguise, though the GM won't factor in the difference in ancestry when determining the DC of your Deception check.
- You can Dismiss this spell.

> [!info] Heighten
>- **Heightened (3rd):** You gain Darkvision or Low-light vision if the form you assume has that ability.
>- **Heightened (5th):** You can take on the appearance of a Large humanoid. If this increases your size, you gain the effects of the [[Enlarge]] spell.