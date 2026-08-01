---
tags: 
  - creature/type/aberration
  - trait/creature/undead
  - trait/effect/unholy
  - trait/effect/incorporeal
statblock: inline
name: "Shadow"
level: 4
format: 1_0
---
# Shadow

[[Shadow Lore]]
**Recall Knowledge - Undead(Religion)**: DC 19
**Unspecific Lore**: DC 17
**Specific Lore**: DC 14

he mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light.


```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Shadow"
level: "Creature 4"
size: "Medium"
trait_02: "[[Undead]]"
trait_03: "[[Unholy]]"
trait_04: "[[Incorporeal]]"
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; __[[Darkvision]]__;"
languages: "Necril; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +10; __Stealth__: +14;"
abilityMods: [-5, 4, 0, -2, 2, 3]

ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__: +8; __Ref__: +14; __Will__: +12;"
hp: 40
health:
  - name: HP
    desc: "40 ([[Void Healing]]); __Immunities__ bleed, death effects, disease, paralyzed, poison, unconscious; __Resistances__ all 5 (except force, _ghost touch_, spirit, or vitality; double resistance vs. non-magical; **Weaknesses** light vulnerability"

abilities_mid:
  - name: Light Vulnerability
    desc: "Attacks against the shadow are treated as magical if made by a creature who is in magical light or with an object that is in magical light (such as from the light spell)."
  - name: Slink in Shadows
    desc: "The shadow can Hide or end its Sneak in a creature's or object's shadow."
  - name: Shadow Spawn
    desc: "When a creature's shadow is pulled free by Steal Shadow, it becomes a shadow spawn under the command of the shadow that created it. This shadow spawn doesn't have Steal Shadow and is perpetually and incurably [[Clumsy]] 2. If the creature the shadow spawn was pulled from dies, the shadow spawn becomes a full-fledged, autonomous shadow. If the creature recovers from its enfeeblement, its shadow returns to it and the shadow spawn is extinguished."

speed: fly 30 feet

attacks:
  - name: Melee Shadow Hand
    desc: "⬻ +15 (+10/+5) ([[finesse]], [[magical]]); __Damage__ 2d6+3 void"
  - name: Steal Shadow
    desc: "⬻ (divine) **Requirements** The shadow hit a living creature with a shadow hand Strike on its previous action; **Effect** The shadow pulls at the target's shadow, making the creature [[Enfeebled]] 1. This is cumulative with other enfeebled conditions from shadows, to a maximum of enfeebled 4. If this increases a creature's enfeebled value to 3 or more, the target's shadow is separated from its body (see shadow spawn). The enfeebled value from Steal Shadow decreases by 1 every hour."

sourcebook: "_Monster Core_, pg. 306"
```

![[Shadow.webp]]]


```encounter-table
name: Shadow
creatures:
  - 1: Shadow
```