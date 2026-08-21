---
tags:
  - action/spell
  - spell/rank/9
  - trait/rarity/uncommon
  - trait/ability/concentrate
  - trait/generic/manipulate
level: 9
format: 1_0
---
# Detonate Magic [](#Actions "Two-Action") &emsp;*(Spell 9)*

  [Uncommon](Uncommon.md "Uncommon Rarity Trait") [Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait")
**Description:** You cause the magic within the target to dissipate in a destructive explosion.

**Traditions:** arcane, primal
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Targets:** 1 magic item or spell effect
**Defense:** [[Basic Saving Throw|Basic]] Reflex
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You attempt to [[Counteracting|Counteract]] the target.
	- If the attempt succeeds, an explosion of magical force deals 8d6 force damage with a basic Reflex save.
		- If you successfully counteract the magic of an item, it's deactivated for 1 week (or destroyed on a critical success) and the explosion is a 5-foot emanation from the item.
		- If you successfully counteract a spell, the effect ends and the explosion affects either all creatures in the spells' area or the target of the spell and all creatures in a 5-foot emanation around it.