---
tags: 
  - creature/type/construct
  - trait/creature/construct
  - trait/creature/mindless
statblock: inline
name: "Animated Broom"
level: -1
format: 1_0
---
# Animated Broom

[[Animated Object Lore]]
**Recall Knowledge - Construct(Arcana, Crafting)**: DC 13
**Unspecific Lore**: DC 11
**Specific Lore**: DC 8

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Animated Broom"
level: "Creature -1"
size: "Small"
trait_02: "[[Construct]]"
trait_03: "[[Mindless]]"
modifier: 3
perception:
  - name: "Perception"
    desc: "+3; __[[Darkvision]]__; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +5; "
abilityMods: [0, +1, 0, -5, 0, -5]

speed: 15 feet

ac: 15
armorclass:
  - name: AC
    desc: "15 (13 when broken); __Fort__: +3; __Ref__: +6; __Will__: +3; construct armor"
hp: 6
health:
  - name: HP
    desc: "6; **Hardness** 2; **Immunities** bleed, death effects, disease, doomed, drained, fatigued, healing, mental, nonlethal attacks, paralyzed, poison, sickened, spirit, unconscious, vitality, void; **Construct Armor** Like normal objects, animated objects have Hardness. This Hardness reduces any damage it takes by an amount equal to the Hardness. Once reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks, removing the Hardness and reducing its Armor Class to 13."

attacks:
  - name: Melee bristles
    desc: "⬻ +6 (+2/-2) ([[agile]], [[finesse]], [[magical]]); __Damage__ 1d4 bludgeoning plus dust"
  - name: Dust
    desc: "A creature hit by an animated broom's bristles must succeed at a DC 15 Fortitude save or spend its next action coughing. Even if hit by multiple dust attacks, the creature has to spend only 1 action coughing to clear the dust out. A creature who doesn't breathe is immune to this effect."

sourcebook: "_Monster Core_, page 18."
```

```encounter-table
name: Animated Broom
creatures:
  - 1: Animated Broom
```