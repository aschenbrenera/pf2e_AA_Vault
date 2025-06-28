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
WHERE format != "1_0" and
contains(tags, "action")
SORT file.mtime DESC
LIMIT 10
```

# Custom Search
```dataview  
LIST
WHERE contains(tags, "action/core") and
!contains(tags, "action/core/basic")
SORT file.name
```
