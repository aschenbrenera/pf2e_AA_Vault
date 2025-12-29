---
tags:
  - campaign
---
# Players

## Base Stats
```dataview  
TABLE WITHOUT ID link(file.name) AS "Character", perception as "Perc.", ac AS "AC", fort AS "Fort", ref AS "Ref", will as "Will", dc as "Class DC"
FROM "custom_campaign/PCs"
SORT file.name
```

## Secret Checks
```dataview  
TABLE WITHOUT ID link(file.name) AS "Character", deception, diplomacy, stealth, arcana, crafting, medicine, nature, occultism, religion, society
FROM "custom_campaign/PCs"
SORT file.name
```

# Lookups
- !!!col
   - 1
     ## Skills
     ```dataview
     LIST
     FROM "Rules/Skills"
     SORT file.name
     ```
   - 1
     ## Actions
     ```dataview
     LIST
     FROM "Rules"
     WHERE 
     contains(tags, "action/core")
     SORT file.name     
     ```
   - 1
     ## Exploration
     ```dataview
     LIST
     FROM "Rules"
     WHERE 
     contains(tags, "activity_exploration/core")
     SORT file.name     
     ```
   - 1
     ## Conditions
     ```dataview
     LIST
     FROM "Rules"
     WHERE contains(tags, "condition") 
     SORT file.name
     ```