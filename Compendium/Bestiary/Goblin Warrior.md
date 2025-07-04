---
aliases: "Goblin Warrior"
tags: 
  - creature/type/humanoid
statblock: inline
name: "Goblin Warrior"
level: -1
format: 1_0
---
# Goblin Warrior

[[Goblin Lore]]
**Recall Knowledge - Humanoid(Society)**: DC 13  
**Unspecific Lore**: DC 11  
**Specific Lore**: DC 8

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Goblin Warrior"
level: "Creature -1"
size: "Small"
trait_03: "Goblin"
trait_04: "Humanoid"
modifier: 2
perception:
  - name: "Perception"
    desc: "Perception +2; __[[Darkvision]]__;"
languages: "Common, Goblin; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +5; __Athletics__: +2; __Nature__: +1; __Stealth__: +5; "
abilityMods: [0, 3, 1, 0, -1, 1]

abilities_mid:
  - name: "Goblin Scuttle"
    desc: "⬲ __Trigger__ A goblin ally ends a move action adjacent to the warrior. __Effect__  The goblin warrior [[Step|Steps]]."
abilities_top:
  - name: Items
    desc: "dogslicer, leather armor, shortbow (10 arrows);"

speed: 25 feet

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +5; __Ref__: +7; __Will__: +3;"
hp: 6
health:
  - name: HP
    desc: "6; "

attacks:
  - name: Melee dogslicer
    desc: "⬻ +7 (+3/-1) ([[agile]], [[backstabber]], [[finesse]]); __Damage__ 1d6 slashing"
  - name: Ranged shortbow
    desc: "⬻ +7 (+2/-3) ([[deadly|deadly 1d10]], [[range-increment|range increment 60 feet]], [[reload|reload 0]]); __Damage__ 1d6 piercing"

sourcebook: "_Monster Core_, page 174."
```

```encounter-table
name: Goblin Warrior
creatures:
  - 1: Goblin Warrior
```