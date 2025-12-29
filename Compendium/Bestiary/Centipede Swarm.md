---
tags: 
  - creature/type/animal
  - creature/type/swarm
statblock: inline
name: "Centipede Swarm"
level: 3
format: 1_0
---
# Centipede Swarm

[[Centipede Lore]]
**Recall Knowledge - Animal (Nature)**: DC 18
**Unspecific Lore**: DC 16
**Specific Lore**: DC 13

Swarms of centipedes are dangerous indeed, ravenous carpets of skittering hunger capable of devouring a traveler whole in a matter of minutes. Kobolds and mitflits are both known to incorporate swarms of centipedes into cunning traps.

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Centipede Swarm"
level: "Creature 3"
size: "Large"
trait_03: "[[Animal]]"
trait_04: "[[Swarm]]"
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; [[Darkvision]]; [[Tremorsense]] (imprecise) 30"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +9; __Athletics__: +7; __Stealth__: +9; "
abilityMods: [2, 4, 3, -5, 0, -4]

speed: 30 feet, climb 30 feet

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +8; __Ref__: +11; __Will__: +5;"
hp: 30
health:
  - name: HP
    desc: "30;  **Immunities** grabbed, precision, prone, restrained, [[swarm mind]]; **Resistances** bludgeoning 5, piercing 5, slashing 2; **Weaknesses** area damage 5, [[splash]] damage 5"

attacks:
  - name: Swarming Bites
    desc: "⬻ Each enemy in the swarm's space takes 1d8 piercing damage (DC 20 basic Reflex save) plus centipede swarm venom."
  - name: Centipede Swarm Venom
    desc: "([[Poison]]): **Saving Throw** DC 20 Fortitude; **Maximum Duration** 6 rounds; **Stage 1** 1d6 poison damage and Off-guard (1 round); **Stage 2** 1d8 poison damage, clumsy 1, and Off-guard (1 round)"

sourcebook: "_Monster Core_, page 59."
```

```encounter-table
name: Centipede Swarm
creatures:
  - 1: Centipede Swarm
```