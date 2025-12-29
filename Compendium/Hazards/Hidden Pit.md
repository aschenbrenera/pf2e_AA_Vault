---
tags: 
  - hazard
statblock: inline
name: "Hidden Pit"
level: 0
format: 1_0
---
# Hidden Pit

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
name: "Hidden Pit"
level: "Hazard 0"
trait_02: "Mechanical"
trait_03: "Trap"
armorclass:
  - name: AC
    desc: "10; **Fort** 1, **Ref** 1"
abilities_top:
  - name: "Stealth"
    desc: "DC 18 (or 0 if disabled or broken)"
  - name: "Description"
    desc: "A wooden trapdoor covers a pit that’s 10 feet square and 20 feet deep."
attacks:
  - name: "Trapdoor Hardness"
    desc: "3; **Trapdoor HP** 12 (BT 6); **Immunities** critical hits, precision damage, [[Item Damage|Object Immunities]]"
  - name: "Disable"
    desc: "Thievery DC 12 to remove trap door."
  - name: "Pitfall Trigger"
    desc: "A creature walks onto the trapdoor; **Effect** The triggering creature falls in and takes falling damage (typically 10 bludgeoning). The creature can use the [[Grab an Edge]] reaction to avoid falling."
  - name: "Reset"
    desc: "Creatures can still fall into the trap, but the trapdoor must be rest manually to become hidden again."

sourcebook: "GM Core 102"
```

```encounter-table
name: Hidden Pit
creatures:
  - 1: Hidden Pit
```