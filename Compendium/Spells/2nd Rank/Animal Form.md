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
# Animal Form  [](#Actions "Two-Action") &emsp;*(Spell 2)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Polymorph](Polymorph.md "Effect Trait")
**Description:** You call upon primal energy to transform yourself into an animal battle form.

**Traditions:** primal 
**Catalysts:** [Feral Linguist](https://2e.aonprd.com/Equipment.aspx?ID=3724)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Duration:** 1 minute
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You transform yourself into a Medium animal battle form. While in this form, you gain the [[Animal]] trait. 
- You can Dismiss the spell.  
- When you Cast this Spell, choose a listed battle form. You can decide the specific type of animal (such as lion or snow leopard for cat), but this has no effect on the form's Size or statistics.
- You gain the following statistics and abilities regardless of which animal you choose:
	- AC = 16 + your level. Ignore your armor's check penalty and Speed reduction.
	- 5 temporary Hit Points.
	- Low-light vision and Imprecise Scent 30 feet.
	- One or more Unarmed melee attacks specific to your battle form, which are the only attacks you can Strike with.
		- You're trained with them.
		- Your attack modifier is +9, and your damage bonus is +1. If your unarmed attack bonus is higher, you can use it instead.
		- These attacks are Strength based (for the purpose of the Enfeebled condition, for example).
	- Athletics modifier of +9, unless your own is higher.
- You also gain specific abilities based on the animal you choose:
	- **Ape** Speed 25 feet, climb 20 feet; Melee [](#Actions "Single Action") fist, Damage 2d6 bludgeoning.
	- **Bear** Speed 30 feet; **Melee** [](#Actions "Single Action") jaws, **Damage** 2d8 piercing; **Melee** [](#Actions "Single Action") claw (agile), **Damage** 1d8 slashing.
	- **Bull** Speed 30 feet; **Melee** [](#Actions "Single Action") horn, **Damage** 2d8 piercing.
	- **Canine** Speed 40 feet; **Melee** [](#Actions "Single Action") jaws, **Damage** 2d8 piercing.
	- **Cat** Speed 40 feet; **Melee** [](#Actions "Single Action") jaws, **Damage** 2d6 piercing; **Melee** [](#Actions "Single Action") claw (agile), **Damage** 1d10 slashing.
	- **Deer** Speed 50 feet; **Melee** [](#Actions "Single Action") antler, **Damage** 2d6 piercing.
	- **Frog** Speed 25 feet, swim 25 feet; **Melee** [](#Actions "Single Action") jaws, **Damage** 2d6 bludgeoning; **Melee** [](#Actions "Single Action") tongue (reach 15 feet), **Damage** 2d4 bludgeoning.
	- **Shark** swim 35 feet; **Melee** [](#Actions "Single Action") jaws, **Damage** 2d8 piercing; breathe underwater but not in air.
	- **Snake** Speed 20 feet, climb 20 feet, swim 20 feet; **Melee** [](#Actions "Single Action") fangs, **Damage** 2d4 piercing plus 1d6 poison.

> [!info] Heighten
>- **Heightened (3rd):** You instead gain 10 temporary HP, AC = 17 + your level, attack modifier +14, damage bonus +5, and Athletics +14.
>- **Heightened (4th):** Your battle form is Large and your attacks have 10-foot reach. You instead gain 15 temporary HP, AC = 18 + your level, attack modifier +16, damage bonus +9, and Athletics +16.
>- **Heightened (5th):** Your battle form is Huge and your attacks have 15-foot reach. You instead gain 20 temporary HP, AC = 18 + your level, attack modifier +18, damage bonus +7 and double the number of damage dice, and Athletics +20.