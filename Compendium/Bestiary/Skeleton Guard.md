---
tags: 
  - creature/type/undead
statblock: inline
name: "Skeleton Guard"
level: -1
format: 1_0
---
# Skeleton Guard

[[Skeleton Lore]]
**Recall Knowledge - Undead(Religion)**: DC 13  
**Unspecific Lore**: DC 11  
**Specific Lore**: DC 8

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Skeleton Guard"
level: "Creature -1"
size: "Medium"
trait_03: "[[Mindless]]"
trait_04: "[[Skeleton]]"
trait_05: "[[Undead]]"
trait_06: "[[Unholy]]"
modifier: 2
perception:
  - name: "Perception"
    desc: "+2; __[[Darkvision]]__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +6; __Athletics__: +3; "
abilityMods: [2, 4, 0, -5, 0, 0]

abilities_top:
  - name: Items
    desc: "scimitar, [[Shortbow]] (20 arrows);"

speed: 25 feet

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +2; __Ref__: +8; __Will__: +2;"
hp: 4
health:
  - name: HP
    desc: "4 ([[void healing]]); __Immunities__ bleed, death effects, disease, mental, paralyzed, poison, unconscious; __Resistances__ cold 5, electricity 5, fire 5, piercing 5, slashing 5"

attacks:
  - name: Melee Scimitar
    desc: "⬻ +6 (+1/-4) ([[forceful]], [[sweep]]); __Damage__ 1d6+2 (1d6+2) slashing"
  - name: Melee Claw
    desc: "⬻ +6 (+2/-2) ([[agile]], [[finesse]]); __Damage__ 1d4+2 (1d4+2) slashing"
  - name: Ranged Shortbow
    desc: "⬻ +6 (+1/-4) ([[deadly|deadly 1d10]], [[range-increment|range increment 60 feet]], [[reload|reload 0]]); __Damage__ 1d6 (1d6) piercing"

sourcebook: "_Monster Core_, pg. 312"
```

```encounter-table
name: Skeleton Guard
creatures:
  - 1: Skeleton Guard
```