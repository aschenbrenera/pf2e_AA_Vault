---
tags:
  - action/spell
  - spell/rank/7 
  - trait/rarity/uncommon
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/extradimensional
level: 7
format: 1_0
---
# Planar Palace &emsp;*(Spell 7)*

  [Uncommon](Uncommon.md "Uncommon Rarity Trait") [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Extradimensional](Extradimensional.md "Effect Trait") 
**Description:** You grow an extradimensional demiplane consisting of a spacious dwelling with a single entrance.

**Traditions:** arcane, occult
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Cast:** 1 minute
**Range:** 30 feet
**Duration:** Until your next daily preparations
**Activity:** 1 minute

## Mechanical Rules

- You grow an extradimensional demiplane consisting of a spacious dwelling with a single entrance.
	- The entrance connects to the plane where you Cast the Spell, appearing anywhere within the spell's range as a faint, shimmering, vertical rectangle 5 feet wide and 10 feet high.
	- You designate who can enter when you Cast the Spell. Once inside, you can shut the entrance, making it Invisible. You and the creatures you designated can reopen the door at will.  
	- Inside, the demiplane appears to be a mansion featuring a magnificent foyer and numerous opulent chambers.
		- The mansion can have any floor plan you imagine as you Cast the Spell, provided it fits within a space 40 feet wide, 40 feet deep, and 30 feet tall.
		- While the entrance to the mansion is closed, effects from outside the mansion fail to penetrate it, and vice versa, except for [[Interplanar Teleport]], which can be used to enter the mansion.
		- You can use `Scrying` magic and similar effects to observe the outside only if they're capable of crossing planes.  
		- A staff of up to 24 servants attends to anyone within the mansion. These are like the servant created by the [[Compendium/Spells/1st Rank/Phantasmal Minion|Phantasmal Minion]] spell, though they're visible, with an appearance you determine during casting.
		- The mansion is stocked with enough food to serve a nine-course banquet to 150 people.