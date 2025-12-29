---
tags: 
  - creature/type/aberration
  - trait/creature/abberation
  - trait/creature/mindless
statblock: inline
name: "Grothlut"
level: 3
format: 1_0
---
# Grothlut

[[Fleshwarp Lore]]
**Recall Knowledge - Aberration(Occultism)**: DC 18 
**Unspecific Lore**: DC 16  
**Specific Lore**: DC 13

Sluglike abominations, grothluts are grotesque dregs of the fleshwarping process. While their head and torso are vaguely humanoid, their arms are rubbery and move awkwardly at their sides. Wretched creatures, they moan piteously when other creatures are near, perhaps as the last remnants of their mind pleads to be free from their horrid warped form.  
  
Many fleshwarpers consider the grothlut to be a failure of a creation, as the transformation all but stamps out consciousness. Others disagree, arguing that warping the creature's mind makes it all the more useful, since it becomes pliable and easy to herd. Cultists typically use grothluts as guardians that slowly patrol the edges of their enclaves. Once in position, grothluts can be used as crude shock troops, unleashed to soften enemy forces before more valuable warriors wade in and cut down the enemies who have been nauseated by the grothluts' exploded organs and flesh.

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Grothlut"
level: "Creature 3"
size: "Medium"
trait_03: "[[Aberration]]"
trait_04: "[[Mindless]]"
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; __[[Darkvision]]__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +11; "
abilityMods: [4, -2, 4, -5, 0, -3]

speed: 20 feet

ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__: +11; __Ref__: +5; __Will__: +7;"
hp: 50
health:
  - name: HP
    desc: "50; __Immunities__ acid, mental"

abilities_top:
  - name: Disgusting Demise
    desc: " (acid, poison) When the grothlut is reduced to 0 Hit Points, its digestive organs rupture, unleashing alchemical acid and poison upon all creatures in a 30-foot emanation. Each creature in the area must succeed at a DC 19 Fortitude save or take 2d6 acid damage and become [[Sickened]] 1 (double damage and sickened 2 on a critical failure)."

attacks:
  - name: Melee Claw
    desc: "⬻ +11 (+7/+3) ([[agile]]); __Damage__ 1d6+2 (1d10+8) slashing"
  - name: Ranged Digestive Spew
    desc: "⬻ +7 (+2/-3) (acid, [[splash]], range 15 feet); __Damage__ 2d6 acid damage plus 1d6 acid splash damage"
  - name: Piteous Moan
    desc: "⬻ +6 (+1/-4) ([[auditory]], [[aura]], [[concentrate]], [[emotion]], [[mental]], [[occult]]) 60 feet; Each non-grothlut creature that enters or starts its turn within the area must succeed at a DC 17 Will saving throw or become [[Sickened]] 1 (2 on a critical failure). The creature then becomes temporarily immune for 1 minute. The grothlut can Dismiss this aura. A grothlut usually does not begin moaning until it senses the presence of a non-grothlut creature, and it usually stops once it doesn't sense any more such creatures."

sourcebook: "_Monster Core_, pg. 312"
```

![[Grothlut.webp]]]


```encounter-table
name: Skeleton Guard
creatures:
  - 1: Skeleton Guard
```