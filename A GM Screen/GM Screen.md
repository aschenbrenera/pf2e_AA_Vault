# Players

## Base Stats
```dataview  
TABLE WITHOUT ID link(file.name) AS "Character", perception as "Perc.", ac AS "AC", fort AS "Fort", ref AS "Ref", will as "Will"
FROM "Campaign/PCs"
SORT file.name
```

## Secret Checks
```dataview  
TABLE WITHOUT ID link(file.name) AS "Character", deception, diplomacy, stealth, arcana, crafting, medicine, nature, occultism, religion, society
FROM "Campaign/PCs"
SORT file.name
```

# Lookups

## Skills
```dataview  
LIST
FROM "Rules/Skills"
SORT file.name
```

## Core Actions
```dataview  
LIST
FROM "Rules"
WHERE 
contains(tags, "action/core")
SORT file.name
```