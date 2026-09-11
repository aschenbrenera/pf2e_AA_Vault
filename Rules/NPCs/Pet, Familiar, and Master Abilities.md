---
tags:
  - rules/npc
aliases:
  - Pet Ability
  - Familiar Ability
  - Master Ability
---
# Pet, Familiar, and Master Abilities

#TODO
## Pet Feat Abilities

The following abilities you can choose from the Pet general feat:

- **Amphibious** It gains the amphibious trait, allowing it to breathe in both air and water, and has both a land Speed and a swim Speed, each equal to its highest land Speed or swim Speed.
- **Burrower** It gains a burrow Speed of 5 feet, allowing it to dig Tiny holes.
- **Climber** It gains a climb Speed of 25 feet.
- **Darkvision** It gains darkvision.
- **Echolocation** It can use hearing as a precise sense within 20 feet.
- **Fast Movement** Increase one of the pet's Speeds from 25 feet to 40 feet.
- **Flier** It gains a fly Speed of 25 feet.
- **Manual Dexterity** It can use up to two of its limbs as if they were hands to perform manipulate actions.
- **Scent** It can use scent as an imprecise sense within 30 feet
- **Tough** Your pet's max HP increase by 2 per level

## Familiar Abilities

Familiar abilities primarily affect the familiar itself. A familiar can have no more than one ability that changes its creature trait (such as construct or plant).

```dataview  
TABLE WITHOUT ID link(name) AS "Familiar Ability", source AS "Source"
FROM "Rules/Abilities/Familiar"
WHERE contains(tags, "ability/familiar/familiar")
```

## Master Abilities

Master abilities primarily affect you or the magic that passes between you and your familiar.

```dataview  
TABLE WITHOUT ID link(name) AS "Familiar Ability", source AS "Source"
FROM "Rules/Abilities/Familiar"
WHERE contains(tags, "ability/familiar/master")
```


- **Cantrip Connection:** You can Prepare an additional cantrip or, if you have a repertoire, designate a cantrip to add to your repertoire every time you select this ability; you can retrain it but can't otherwise change it. You must be able to prepare cantrips or add them to your repertoire to select this.  
- **Extra Alchemy:** Your familiar helps you brew items at the start of the day. You can create one additional item with advanced alchemy during your Daily Preparations.  
- **Extra Vial:** Your familiar accretes alchemical liquids in its body. Once per day, you can Interact when your familiar is adjacent to you to gain a versatile vial.  
- **Familiar Focus:** Once per day, your familiar can use 2 actions with the `CONCENTRATE` trait to restore 1 Focus Point to your focus pool, up to your usual maximum. You must have a focus pool to select this.  
- **Innate Surge:** Once per day, you can draw upon your familiar's innate magic to replenish your own. You can cast one innate spell gained from an ancestry feat that you have already cast today. You must still Cast a Spell and meet the spell's other requirements.  
- **Lifelink:** If your familiar would be reduced to 0 HP by damage, as a reaction with the `CONCENTRATE` trait, you can take all the damage, and your familiar takes none. However, special effects that would occur due to that damage (such as snake venom) still apply.  
- **Recall Familiar:** Once per day, you can use a 3-action activity, which has the `CONCENTRATE` trait, to teleport your familiar to your space. Your familiar must be within 1 mile or the attempt to summon it fails. This is a Teleportation effect.  
- **Restorative Familiar:** Once per day, your familiar can use 2 actions with the `CONCENTRATE` trait to give up some of its energy and heal you. It must be in your space to do so. You restore a number of Hit Points equal to 1d8 times half your level (minimum 1d8).  
- **Share Senses:** Once every 10 minutes, you can use a single action with the `CONCENTRATE` trait to project your senses into your familiar. When you do, you lose all sensory information from your own body, but can sense through your familiar's body for up to 1 minute. You can Dismiss this effect.  
- **Spell Battery:** You gain one additional spell slot at least 3 ranks lower than your highest-rank spell slot; you must be able to cast 4th-rank spells using spell slots to select this master ability.  
- **Spell Delivery:** If your familiar is in your space, you can Cast a Spell with a range of touch, transfer its power to your familiar, and command the familiar to deliver the spell. If you do, the familiar uses its 2 actions for the round to move to a target of your choice and touch that target. If it doesn't reach the target to touch it this turn, the spell has no effect.  