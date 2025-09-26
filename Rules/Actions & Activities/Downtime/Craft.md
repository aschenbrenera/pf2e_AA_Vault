---
tags:
  - activity_downtime/core
  - trait/ability/downtime
  - trait/generic/manipulate
  - custom_group/creation
---
# Craft

[Downtime](Downtime.md "Action & Ability Trait") [Manipulate](Manipulate.md "General Trait")
**Description:** You can make an item from raw materials.

**Skill:** [[Crafting]] (Trained)
**Requirements:** You are trained in Crafting.

## Mechanical Rules

- To Craft an item, you must meet the following requirements:
	- You need the [[Alchemical Crafting]] skill feat to create alchemical items and the [[Magical Crafting]] skill feat to create magic items.
	- The item is your level or lower. An item that doesn't list a level is level 0.
		- If the item is 9th level or higher, you must be a master in Crafting.
		- If the item is 17th or higher, you must be legendary in Crafting.
	- The item must be common, or you must otherwise have access to it.
	- You have an appropriate set of tools and, in many cases, a workshop. For example, you need access to a smithy to forge a metal shield, or an alchemist's lab to produce alchemical items.
	- You must supply raw materials worth at least half the item's Price. You always expend at least that amount of raw materials when you Craft successfully. If you're in a settlement, you can usually spend currency to get the amount of raw materials you need, except in the case of rarer precious materials.
- You attempt a Crafting check after you spend 2 days of work setting up, or 1 day if you have the item's [[Formulas|Formula]]. The GM determines the DC to Craft the item based on its level, rarity, and other circumstances. 
  > [!success-degree]
  >- **Critical Success**: Your attempt is successful. Each additional day spent Crafting reduces the materials needed to complete the item by an amount based on your level + 1 and your proficiency rank in Crafting.
  >- **Success**: Your attempt is successful. Each additional day spent Crafting reduces the materials needed to complete the item by an amount based on your level and your proficiency rank.
  >- **Failure**: You fail to complete the item. You can salvage the raw materials you supplied for their full value. If you want to try again, you must start over.
  >- **Critical Failure**: You fail to complete the item. You ruin 10% of the raw materials you supplied, but you can salvage the rest. If you want to try again, you must start over.
- If your attempt to create the item is successful, you expend the raw materials you supplied. You can pay the remaining portion of the item's Price in materials to complete the item immediately, or you can spend additional downtime days working on it.
	- For each additional day you spend, reduce the value of the materials you need to expend to complete the item. This amount is determined using the Income Earned table, based on your proficiency rank in Crafting and using your own level instead of a task level.  
	  - After any of these downtime days, you can complete the item by spending the remaining portion of its Price in materials. If the downtime days you spend are interrupted, you can return to finish the item later, continuing where you left off. 

## Table Income Earned

|**Task Level**|**DC**|**Failed**|**Trained**|**Expert**|**Master**|**Legendary**|
|---|---|---|---|---|---|---|
|0|14|1 cp|5 cp|5 cp|5 cp|5 cp|
|1|15|2 cp|2 sp|2 sp|2 sp|2 sp|
|2|16|4 cp|3 sp|3 sp|3 sp|3 sp|
|3|18|8 cp|5 sp|5 sp|5 sp|5 sp|
|4|19|1 sp|7 sp|8 sp|8 sp|8 sp|
|5|20|2 sp|9 sp|1 gp|1 gp|1 gp|
|6|22|3 sp|1 gp, 5 sp|2 gp|2 gp|2 gp|
|7|23|4 sp|2 gp|2 gp, 5 sp|2 gp, 5 sp|2 gp, 5 sp|
|8|24|5 sp|2 gp, 5 sp|3 gp|3 gp|3 gp|
|9|26|6 sp|3 gp|4 gp|4 gp|4 gp|
|10|27|7 sp|4 gp|5 gp|6 gp|6 gp|
|11|28|8 sp|5 gp|6 gp|8 gp|8 gp|
|12|30|9 sp|6 gp|8 gp|10 gp|10 gp|
|13|31|1 gp|7 gp|10 gp|15 gp|15 gp|
|14|32|1 gp, 5 sp|8 gp|15 gp|20 gp|20 gp|
|15|34|2 gp|10 gp|20 gp|28 gp|28 gp|
|16|35|2 gp, 5 sp|13 gp|25 gp|36 gp|40 gp|
|17|36|3 gp|15 gp|30 gp|45 gp|55 gp|
|18|38|4 gp|20 gp|45 gp|70 gp|90 gp|
|19|39|6 gp|30 gp|60 gp|100 gp|130 gp|
|20|40|8 gp|40 gp|75 gp|150 gp|200 gp|
|20 (critical success)|—|—|50 gp|90 gp|175 gp|300 gp|



## Gameplay Interaction

- [[Consumable]] items include alchemical items and magical consumables such as scrolls, potions, and talismans. A character can Craft consumable items in batches of four.


## Skill Feats

| Level | Feat                    | Req. Training    | Short Desc.                      |
| ----- | ----------------------- | ---------------- | -------------------------------- |
| 1     | [[Alchemical Crafting]] | Trained Crafting | Create alchemical items.         |
| 2     | [[Communal Crafting]]   | Expert Crafting  | Help or Get Help crafting items. |
| 2     | [[Magical Crafting]]    | Expert Crafting  | Create magical items.            |

