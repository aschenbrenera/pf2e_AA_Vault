---
tags:
  - action/spell
  - spell/rank/1
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/illusion
  - trait/effect/visual
level: 1
format: 1_0
---
# Illusory Disguise [](#Actions "Two-Action") &emsp;*(Spell 1)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Illusion](Illusion.md "Effect Trait") [Visual](Rules/Traits/Effect/Visual.md "Effect Trait")
**Description:** Use illusion to disguise a creature.

**Traditions:** arcane, occult
**Bloodline:** hag
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 30 feet
**Targets:** 1 willing creature
**Duration:** 1 hour
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You create an illusion that causes the target to appear as another creature of the same body shape, and with roughly similar height (within 6 inches) and weight (within 50 pounds).
	- The disguise is typically good enough to hide their identity, but not to impersonate a specific individual.
	- The spell changes their appearance and voice, but not mannerisms.
	- You can change the appearance of its clothing and worn items, such as making its armor look like a dress.
	- Held items are unaffected, and any worn item removed from the creature returns to its true appearance.  
- Casting _illusory disguise_ counts as setting up a disguise for the [[Impersonate]] use of Deception. 
	- It ignores any circumstance penalties the target might take for disguising itself as a dissimilar creature.
	- It gives a +4 status bonus to Deception checks to prevent others from seeing through the disguise, and lets the target add its level to such Deception checks even if untrained.
- You can Dismiss this spell.

> [!info] Heighten
>- **Heightened (3rd):** The target can appear as any creature of the same size, even a specific individual. You must have seen an individual to replicate its appearance, and must have heard its voice to replicate its voice. 
>- **Heightened (4th):** You can target up to 10 willing creatures. If you target multiple creatures, you can choose a different disguise for each target, but none can impersonate a specific individual. You can Dismiss each disguise individually or all collectively.  
>- **Heightened (7th):** As 4th, but you can choose disguises that impersonate specific individuals. You must have seen an individual to replicate its appearance, and must have heard its voice to replicate its voice.

## Gameplay Interaction

- Follows the rules for the `Visual` trait.
    - A visual effect can affect only creatures that can see it. This applies only to visible parts of the effect, as determined by the GM.