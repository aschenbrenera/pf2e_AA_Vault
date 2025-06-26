#obsidian_workpad 

# Recently Modified Files
```dataview  
TABLE WITHOUT ID link(file.name) AS "Recently Modified"
FROM "Rules"
SORT file.mtime DESC
LIMIT 10
```

# Recent Bestiary
```dataview  
TABLE WITHOUT ID link(file.name) AS "Creature Name", level
FROM "Bestiary"
SORT file.mtime DESC
LIMIT 10
```
