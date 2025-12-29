---
tags: 
  - creature/type/construct
statblock: inline
name: "Animated Armor"
level: 2
format: 1_0
---
# Animated Armor

[[Animated Object Lore]]
**Recall Knowledge - Construct(Arcana, Crafting)**: DC 16
**Unspecific Lore**: DC 14
**Specific Lore**: DC 11

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Animated Armor"
level: "Creature 2"
size: "Medium"
trait_02: "[[Construct]]"
trait_03: "[[Mindless]]"
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; __[[Darkvision]]__; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +9; "
abilityMods: [3, -3, 4, -5, 0, -5]

speed: 20 feet

ac: 17
armorclass:
  - name: AC
    desc: "17 (13 when broken); __Fort__: +10; __Ref__: +3; __Will__: +4; construct armor"
hp: 20
health:
  - name: HP
    desc: "20; **Hardness** 9; **Immunities** bleed, death effects, disease, doomed, drained, fatigued, healing, mental, nonlethal attacks, paralyzed, poison, sickened, spirit, unconscious, vitality, void; **Construct Armor** Like normal objects, animated objects have Hardness. This Hardness reduces any damage it takes by an amount equal to the Hardness. Once reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks, removing the Hardness and reducing its Armor Class to 13."

attacks:
  - name: Melee glaive
    desc: "⬻ +10 (+5/+0) ([[deadly|deadly 1d8]], [[forceful]], [[magical]], [[reach]] 10 feet); __Damage__ 1d8+4 slashing"
  - name: Melee gauntlet
    desc: "⬻ +9 (+5/+1) ([[agile]], [[free-hand]], [[magical]]); __Damage__ 1d6+4 bludgeoning"

sourcebook: "_Monster Core_, page 18."
```

```encounter-table
name: Animated Armor
creatures:
  - 1: Animated Armor
```