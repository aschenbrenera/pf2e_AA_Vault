---
tags:
  - action/spell
  - spell/rank/3
  - trait/ability/concentrate
  - trait/generic/manipulate
  - trait/effect/auditory
  - trait/effect/emotion
  - trait/effect/linguistic
level: 3
format: 1_0
---
# Enthrall [](#Actions "Two-Action") &emsp;*(Spell 3)*

[Concentrate](Concentrate.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait") [Auditory](Auditory.md "Effect Trait") [Emotion](Rules/Traits/Effect/Emotion.md "Effect Trait")
**Description:** Your words fascinate your targets.

**Traditions:** arcane, occult 
**Bloodline:** diabolic, fey
```dataviewjs
const deities = dv.pages('"Compendium/Deities"') .where(d => d.cleric_spells?.includes(dv.current().file.name)) .sort(d => d.file.name); dv.paragraph("**Deities:** " + deities.map(d => d.file.link).join(", "));
```

**Range:** 120 feet
**Targets:** all creatures in range
**Defense:** Will
**Duration:** sustained
**Activity:** Two Action ⬥⬥

## Mechanical Rules

- You speak or sing without interruption throughout the casting and duration.
-  If you're speaking (not singing), _enthrall_ gains the `Linguistic` trait.
- Each target must attempt a Will save. The GM might grant a circumstance bonus (to a maximum of +4) if the target is of an opposing religion, ancestry, or political leaning, or is otherwise unlikely to agree with what you're saying.  
	- Each creature that comes within range has to attempt a save when you Sustain the spell.
  > [!success-degree]
  > **Critical Success:** The target is unaffected and notices that you tried to use magic.
  > **Success:** The target needn't pay attention but doesn't notice you tried to use magic (it might notice others are enthralled).
  > **Failure:** The target is [[Fascinated]] with you. It can attempt another Will save if it witnesses actions or speech with which it disagrees. If it succeeds, it's no longer fascinated and is temporarily immune for 1 hour. If the target is subject to a [[Hostile]] action, or if another creature succeeds at a Diplomacy or Intimidation check against it, the fascination ends immediately.
  > **Critical Failure:** As failure, but the target can't attempt a save to end the fascination if it disagrees with you.  