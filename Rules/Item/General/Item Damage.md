---
tags:
  - rules/items
---
# Item Damage

An item can be broken or destroyed if it takes enough damage. Every item has a Hardness value. Each time an item takes damage, reduce any damage the item takes by its Hardness. The rest of the damage reduces the item's Hit Points. Normally an item takes damage only when a creature is directly attacking it—commonly targeted items include doors and traps. A creature that attacks you doesn't normally damage your armor or other gear, even if it hits you. However, the Shield Block reaction can cause your shield to take damage as you use it to prevent damage to yourself, and some monsters have exceptional abilities that can damage your items.  
  
An item that takes damage can become **broken** and eventually destroyed. It becomes broken when its Hit Points are equal to or lower than its **Broken Threshold (BT);** once its Hit Points are reduced to 0, it is **destroyed.** A broken item has the broken condition until Repaired above its Broken Threshold. Anything that automatically makes an item broken immediately reduces its Hit Points to its Broken Threshold if the item had more Hit Points than that when the effect occurred. If an item has no Broken Threshold, then it has no relevant changes to its function due to being broken, but it's still destroyed at 0 Hit Points. A destroyed item can't be Repaired.

## Object Immunities

Inanimate objects and hazards are immune to bleed, death effects, disease, healing, mental effects, nonlethal attacks, poison, spirit, vitality, void, as well as the doomed, drained, fatigued, paralyzed, sickened, and unconscious conditions. Conscious, thinking items are not immune to mental effects. Many objects are immune to other conditions, at the GM’s discretion. For instance, a sword can’t move, so it can’t take a penalty to its Speed, but a spinning blade trap might be affected.


## Material Hardness, Hit Points, and Broken Threshold

| **Material**            | **Hardness** | **HP** | **BT** | **Example Items**                       |
| ----------------------- | ------------ | ------ | ------ | --------------------------------------- |
| Paper                   | 0            | 1      | —      | Book pages, paper fan, scroll           |
| Thin cloth              | 0            | 1      | —      | Kite, silk dress, undershirt            |
| Thin glass              | 0            | 1      | —      | Bottle, spectacles, window pane         |
| Cloth                   | 1            | 4      | 2      | Cloth armor, heavy jacket, sack, tent   |
| Glass                   | 1            | 4      | 2      | Glass block, glass table, heavy vase    |
| Glass structure         | 2            | 8      | 4      | Glass block wall                        |
| Thin leather            | 2            | 8      | 4      | Backpack, jacket, pouch, strap, whip    |
| Thin rope               | 2            | 8      | 4      | Standard adventuring rope               |
| Thin wood               | 3            | 12     | 6      | Chair, club, sapling, wooden shield     |
| Leather                 | 4            | 16     | 8      | Leather armor, saddle                   |
| Rope                    | 4            | 16     | 8      | Industrial rope, ship rigging           |
| Thin stone              | 5            | 16     | 8      | Chalkboard, slate tiles, stone cladding |
| Thin iron or steel      | 5            | 20     | 10     | Chain, steel shield, sword              |
| Wood                    | 5            | 20     | 10     | Chest, simple door, table, tree trunk   |
| Stone                   | 7            | 28     | 14     | Paving stone, statue                    |
| Iron or steel           | 9            | 36     | 18     | Anvil, iron or steel armor, stove       |
| Wooden structure        | 10           | 40     | 20     | Reinforced door, wooden wall            |
| Stone structure         | 14           | 56     | 28     | Stone wall                              |
| Iron or steel structure | 18           | 72     | 36     | Iron plate wall                         |

## Doors, Gates, and Walls

| **Door**        | **Hardness** | **HP** | **BT** |
| --------------- | ------------ | ------ | ------ |
| Wood            | 10           | 40     | 20     |
| Stone           | 14           | 56     | 28     |
| Reinforced wood | 15           | 60     | 30     |
| Iron            | 18           | 72     | 36     |

| **Portcullis**    | **Hardness** | **HP** | **BT** |
| ----------------- | ------------ | ------ | ------ |
| Crumbling masonry | 10           | 40     | 20     |
| Wooden slats      | 18           | 72     | 36     |

| **Wall**          | **Hardness** | **HP** | **BT** |
| ----------------- | ------------ | ------ | ------ |
| Crumbling masonry | 10           | 40     | 20     |
| Wooden slats      | 10           | 40     | 20     |
| Masonry           | 14           | 56     | 28     |
| Hewn stone        | 14           | 56     | 28     |
| Iron              | 18           | 72     | 36     |


