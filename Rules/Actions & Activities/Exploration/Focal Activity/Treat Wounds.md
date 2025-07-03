---
tags:
  - activity_exploration/core
  - trait/ability/exploration
  - trait/effect/healing
  - trait/generic/manipulate
format: 1_0
---
# Treat Wounds

[Exploration](Exploration.md "Action & Ability Trait") [Healing](Healing.md "Effect Trait") [Manipulate](Manipulate.md "General Trait")
**Description:** Attempt to heal a living creature.

**Skill:** [[Medicine]] (Trained)
**Requirements:** You're wearing or holding a [[Healer's Toolkit]]. You are trained in Medicine.

## Mechanical Rules

- You spend 10 minutes treating one injured living creature (targeting yourself, if you so choose).
- The target is then temporarily immune to Treat Wounds actions for 1 hour, but this interval overlaps with the time you spent treating (so a patient can be treated once per hour, not once per 70 minutes).  
- The check DC is usually 15, though the GM might adjust it based on the circumstances, such as treating a patient outside in a storm, or treating magically cursed wounds.
	- If you're an expert in Medicine, you can instead attempt a DC 20 check to increase the Hit Points regained by 10; if you're a master of Medicine, you can instead attempt a DC 30 check to increase the Hit Points regained by 30; and if you're legendary, you can instead attempt a DC 40 check to increase the Hit Points regained by 50. The damage dealt on a critical failure remains the same.  See the table below.
- If you succeed at your check, you can continue treating the target to grant additional healing. If you treat it for a total of 1 hour, double the Hit Points it regains.  
- Attempt a Medicine check:

> [!success-degree] 
>- **Critical Success:** The target regains 4d8 Hit Points (increased at higher DCs) and loses the [[Wounded]] condition. 
>- **Success:** The target regains 2d8 Hit Points (increased at higher DCs) , and loses the Wounded condition.  
>- **Critical Failure:** The target takes 1d8 damage.

| **Proficiency** | **DC** | **Success Healing** | **Critical Healing** |
| --------------- | ------ | ------------------- | -------------------- |
| Trained         | 15     | 2d8                 | 4d8                  |
| Expert*         | 20     | 2d8+10              | 4d8+10               |
| Master*         | 30     | 2d8+30              | 4d8+30               |
| Legendary*      | 40     | 2d8+50              | 4d8+50               |

## Skill Feats

| Level | Feat                   | Req. Training      | Short Desc.                                 |
| ----- | ---------------------- | ------------------ | ------------------------------------------- |
| 1     | [[Natural Medicine]]   | Trained in Nature  | Use Nature to Treat Wounds.                 |
| 2     | [[Continual Recovery]] | Expert in Medicine | Reduce Treat Wounds immunity to 10 minutes. |


