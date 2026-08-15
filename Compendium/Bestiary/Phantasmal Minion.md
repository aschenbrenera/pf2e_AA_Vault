---
tags: 
  - creature/type/undead
  - trait/size/medium
  - trait/creature/mindless
  - trait/effect/force
statblock: inline
name: "Phantasmal Minion"
level: -1
format: 1_0
---
# Phantasmal Minion
#TODO Ability and page number

**Recall Knowledge - Undead(Religion)**: DC 13 
**Unspecific Lore**: DC 11
**Specific Lore**: DC 8

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Phantasmal Minion"
level: "Creature -1"
size: "Medium"
trait_02: "[[Force]]"
trait_03: "[[Mindless]]"
modifier: 0
perception:
  - name: "Perception"
    desc: "+0; __[[Darkvision]]__;"
languages: "none (understands its creator)"
skills:
  - name: "Skills"
    desc: "Stealth: +8;"
abilityMods: [-4, 2, 0, -5, 0, 0]

ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__: +0; __Ref__: +4; __Will__: +0;"
hp: 4
health:
  - name: HP
    desc: "4 __Immunities__ disease, mental, non-magical attacks, paralyzed, poison, precision, spirit, unconscious; **Resistances** all damage 5 (except force or ghost touch)"

speed: fly 30 feet

sourcebook: "_Monster Core_, pg. "
```

```encounter-table
name: Phantasmal Minion
creatures:
  - 1: Phantasmal Minion
```
