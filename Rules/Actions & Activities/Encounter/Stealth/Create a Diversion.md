---
tags:
  - action/core
  - trait/effect/mental
aliases:
  - Diversion
format: 1_0
---
# Create a Diversion [](#Actions "Single Action")

[Mental](Mental.md "Effect Trait")
**Description:** With a gesture, a trick, or some distracting words, you can create a diversion that draws creatures' attention elsewhere. 

**Skill:** [[Deception]] (Untrained)
**Activity:** Single Action ⬥

## Mechanical Rules

- If you use a gesture or trick, this action gains the `Manipulate` trait. If you use distracting words, it gains the `Auditory` and `Linguistic` traits.  
- Whether or not you succeed, creatures you attempt to divert gain a +4 circumstance bonus to their Perception DCs against your attempts to Create a Diversion for 1 minute.
- If this action makes you Hidden to a creature, you become [[Rules/Environment/Sensory/Detection#Observed|Observed]] by it again if any of the following occurs:
	- Your turn ends. This can be negated by performing either a successful [[Hide]] or [[Sneak]] before your turn ends.
	- You attempt to Strike a creature. The creature remains [[Off-Guard]] against that attack, and you then become Observed.
	- If you do anything else except Hide or Sneak.
		- The GM might allow you to perform a particularly unobtrusive action without being noticed, possibly requiring another Stealth check.
		- You become observed just before you act unless the GM determines otherwise. 
- Attempt a single Deception check and compare it to the Perception DCs of the creatures whose attention you're trying to divert.

> [!success-degree]
>- **Success:** You become [[Hidden]] to each creature whose Perception DC is less than or equal to your result. (Even if you don't have cover or concealment.)
>- **Failure:** You don't divert the attention of any creatures whose Perception DC exceeds your result, and those creatures are aware you were trying to trick them.

## Gameplay Interaction

- Follows the rules for the [[Linguistic]] trait.
	- A linguistic effect that targets a creature works only if the target understands the language you are using.

## Skill Feats

| Level | Feat                  | Req. Training     | Short Desc.                                        |
| ----- | --------------------- | ----------------- | -------------------------------------------------- |
| 1     | [[Lengthy Diversion]] | Trained Deception | Can extend your hidden duration after a diversion. |
| 1     | [[Subtle Theft]]      | Trained Thievery  | Better at taking items while avoiding detection.   |
| 2     | [[Confabulator]]      | Expert Deception  | Reduce penalties for repeated lies and deceptions. |
