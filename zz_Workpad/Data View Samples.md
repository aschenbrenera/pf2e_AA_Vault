#obsidian/workpad 

# Recently Modified Files
```dataview  
TABLE WITHOUT ID link(file.name) AS "Recently Modified"
FROM "Rules"
SORT file.mtime DESC
LIMIT 10
```

# Files Not in the current format
```dataview  
LIST
FROM "Rules"
WHERE format != "1_0"and
!contains(tags, "rules/trait")
SORT file.mtime DESC
LIMIT 10
```

# Custom Search
```dataview  
LIST
FROM "Rules"
WHERE format != "1_0" and
!contains(tags, "rules/trait")
SORT file.name
LIMIT 20
```
