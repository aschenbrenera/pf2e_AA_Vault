---
tags:
  - action/spell
  - spell/rank/2
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/illusion
level: 6
format: 1_0
---
# Mislead [](#Actions "Two-Action") &emsp;*(Spell 6)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Illusion](Illusion.md "Effect Trait")
**Description:** You create an illusion of yourself as you become invisible. 

**Traditions:** arcane, occult
**Bloodline:** fey
**Catalysts:** [Stolen Countenance](https://2e.aonprd.com/Equipment.aspx?ID=5066)
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Duration:** sustained up to 1 minute
**Activity:** Two Action ⬥⬥

## Mechanical Rules

- You turn yourself [[Invisible]] and create an illusory duplicate of yourself.
- When you Sustain the spell, you can mentally dictate a course of action for your duplicate to follow that round.
- Your duplicate acts as though it had your full number of actions, though it can't actually affect anything in the environment.
- Both the duplicate and your invisibility persist for the spell's duration.
- Performing a hostile action doesn't end mislead's invisibility, just like a 4th-rank [[Invisibility]] spell. 
- A creature that determines the duplicate is an illusion doesn't necessarily know you're invisible, and one that can see your invisible form doesn't necessarily know your duplicate is an illusion.  
- If you Cast a Spell, attack, or otherwise interact with another creature, as a part of that action you can attempt a Deception check against observers' Perception DCs to convince them your duplicate used that action. This doesn't fool anyone who's aware your duplicate is an illusion, nor does it work if the attack obviously couldn't have come from the duplicate.
	- For instance, if you fired a ray, you could make it look like it came from the duplicate as long as the duplicate was positioned appropriately, but if you attacked with a sword and your duplicate was across the room from the target, your Deception check would automatically fail.