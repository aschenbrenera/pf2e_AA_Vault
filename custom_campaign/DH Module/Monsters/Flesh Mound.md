---
tags: 
  - creature/type/aberration
  - trait/creature/abberation
statblock: inline
name: "Flesh Mound"
level: 6
format: 1_0
---
# Flesh Mound

[[Fleshwarp Lore]]
**Recall Knowledge - Aberration(Occultism)**: DC 20 
**Unspecific Lore**: DC 18
**Specific Lore**: DC 15

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Flesh Mound"
level: "Creature 6"
size: "Medium"
trait_02: "[[Aberration]]"
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; __[[Darkvision]]__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +12, __Athletics__: +13; "
abilityMods: [2, 3, 4, -3, 3, 0]

ac: 21
armorclass:
  - name: AC
    desc: "17; __Fort__: +15; __Ref__: +12; __Will__: +10;"
hp: 120
health:
  - name: HP
    desc: "120; ;; **Immunities** Blinded, Prone, Grappled; **Weaknesses** bludgeoning 5"

abilities_mid:
  - name: Mother's Lullaby
    desc: "If a player uses their action to hum or play _Waltz for Klara_ and succeeds on a DC 10 Performance check, the mound exposes its heart until the start of it's next turn."
  - name: Innocent Heart
    desc: "The center of the mound conceals its 'heart', a large, misshapen rib cage. Within the rib cage hovers the infant corpse of Walter Durst. Walter's corpse has AC 15. Each time Walter's corpse takes damage, the flesh mound takes twice as much damage."
  - name: Oozing Body
    desc: "The flesh mound can move through spaces occupied by enemy creatures, as well as spaces smaller than a Large creature."

speed: 15 feet

attacks:
  - name: Melee Tentacle Slam
    desc: "⬻ +14 (+9/+4) ([[finesse]], reach 10 feet); __Damage__ 2d8+5 bludgeoning and Grab"
  - name: [[Constrict]]
    desc: "⬻ __Damage__ 1d8+9 bludgeoning and Basic Fortitude DC 22 (grabbed only)"
  - name: Ranged Bone Splinters
    desc: "⬻ +14 (+9/+4) (range 30 feet); __Damage__ 2d6 piercing plus 1d4 persistent bleed damage"
  - name: [[Engulf]]
    desc: "⬻⬻ +DC 22, 3d8 piercing, Escape DC 22, Rupture 8"
  - name: Lash Out
    desc: "⬲ (reach 10 feet); **Trigger** Taking melee damage; **Effect** [[Trip]] the target."
  - name: Roll
    desc: "⬲ **Trigger** Taking ranged damage; **Effect** Moves up to it's speed towards an enemy. If it reaches that enemy, it attempts to [[Shove]]."

sourcebook: "Custom"
```

![[Walter.jpg]]

```encounter-table
name: Flesh Mound
creatures:
  - 1: Flesh Mound
```