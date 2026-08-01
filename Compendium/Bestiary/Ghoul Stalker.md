---
tags: 
  - creature/type/undead
  - trait/creature/undead
  - trait/creature/ghoul
  - trait/effect/unholy
statblock: inline
name: "Ghoul Stalker"
level: 1
format: 1_0
---
# Ghoul Stalker

[[Ghoul Lore]]
**Recall Knowledge - Undead(Religion)**: DC 15 
**Unspecific Lore**: DC 13
**Specific Lore**: DC 10

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Ghoul Stalker"
level: "Creature 1"
size: "Medium"
trait_02: "[[Undead]]"
trait_03: "[[Ghoul]]"
trait_04: "[[Unholy]]"
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; __[[Darkvision]]__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +7; __Athletics__: +8; Stealth: +7; Survival: +5;"
abilityMods: [1, 4, 1, 1, 2, 2]

ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__: +4; __Ref__: +9; __Will__: +5;"
hp: 16
health:
  - name: HP
    desc: "16 ([[Void Healing]]); __Immunities__ bleed, death effects, disease, paralyzed, poison, unconscious;"
    
abilities_mid:
  - name: "Grave Knowledge"
    desc: "**Frequency** once per hour; **Effect** The ghoul calls upon knowledge it retains from one creature it has consumed in the past 7 days. The ghoul attempts a skill check using a skill in which the consumed creature was trained (if it's unclear whether the creature was trained, the GM decides). The ghoul is treated as trained and uses +7. This takes the same amount of actions or time as usual for the check."
  - name: "Forbidden Cravings"
    desc: "([[curse]]) A creature can still eat and drink while sickened by this curse; **Saving Throw** Will DC 17; **Stage 1** carrier with no ill effects (1 day); **Stage 2** 2d6 void damage and the target is sickened 1 until it consumes raw meat (1 day); **Stage 3** as stage 2; **Stage 4** as stage 2 unless the target has consumed raw meat in the past 24 hours, then it takes 4d6 void damage and is sickened 2 until it consumes raw meat; **Stage 5** if the creature has eaten raw meat in the past 24 hours, it dies and rises as a ghoul, if not, it returns to stage 4"
  - name: [[Stench]]
    desc: "([[Aura]] [[Olfactory]]) 10 feet, DC 14"

speed: 25 feet, burrow 5 feet

attacks:
  - name: Melee Jaws
    desc: "⬻ +9 (+4/-1) ([[finesse]]); __Damage__ 1d8+1 piercing"
  - name: Melee Claw
    desc: "⬻ +9 (+5/+1) ([[agile]], [[finesse]]); __Damage__ 1d6+1 slashing plus [[Grab]]"
  - name: Consume Flesh
    desc: "⬻ (manipulate) **Requirements** The ghoul is adjacent to the corpse of a creature that died within the last hour; **Effect** The ghoul devours a chunk of the corpse and regains 1d6 Hit Points plus 1d6 for every 2 levels the ghoul has. It can regain Hit Points from any given corpse only once."
  - name: Ghoul Whispers
    desc: "⬻ ([[auditory]], [[linguistic]], [[occult]]) **Requirement** A grabbed, paralyzed], restrained, or unconscious creature is within the ghoul's reach; **Effect** The ghoul whispers dark thoughts and vile cravings into the creature's ears. The creature must save against DC 17 for the forbidden cravings curse."
  - name: Swift Leap
    desc: "⬻ (Move) The ghoul jumps up to half its Speed. This movement doesn't trigger reactions."

sourcebook: "_Monster Core_, pg. 312"
```

```encounter-table
name: Ghoul Stalker
creatures:
  - 1: Ghoul Stalker
```
