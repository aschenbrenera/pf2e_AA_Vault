---
tags:
  - action/spell
  - spell/rank/2
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/illusion
level: 1
format: 1_0
---
# Embed Message [](#Actions "Two-Action") &emsp;*(Spell 2)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Illusion](Illusion.md "Effect Trait")
**Description:** 

**Traditions:** arcane, occult
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** Touch
**Targets:** 1 object or willing creature
**Duration:** unlimited
**Cast:** Two Action ⬥⬥

## Mechanical Rules

- You specify a trigger and a message up to 25 words long.
	- When the specified trigger occurs within 30 feet of the target, illusory text of your message circles the target accompanied by a disembodied voice.
	- You can choose a language you know for the text and speech, and can choose what the voice sounds like.
	- Once the message is completed, the spell ends.

> [!info] Heighten
>- **Heightened (4th):** You can add a simple sensory component to emphasize the message, such as an odor, visual effect, or physical sensation. This addition is obviously illusory and part of the message, lasting only while the message is being read.
>- **Heightened (6th):** As 4th rank, but you can choose how many times the spell repeats the message before it ends; there is no limit to the number of repetitions.
