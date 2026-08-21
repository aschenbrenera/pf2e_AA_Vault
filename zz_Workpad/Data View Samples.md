#obsidian/workpad 
#tool

# Recently Modified Files
```dataview  
TABLE WITHOUT ID link(file.name) AS "Recently Modified"
FROM "Rules"
SORT file.mtime DESC
LIMIT 10
```

# Dead Links
```dataview  
TABLE without id
out AS "Uncreated files", file.link as "Origin"
FLATTEN file.outlinks as out
WHERE !(out.file) AND !contains(meta(out).path, "/")
SORT file.link ASC
```

# Files Not in the current format
```dataview  
LIST
FROM "Rules"
WHERE format != "2.0"and
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

# Fix Legacy Traits
```dataview  
LIST
WHERE 
contains(tags, "trait/generic/concentrate") 
SORT file.name
LIMIT 20
```