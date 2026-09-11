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
WHERE format != 2
and !contains(tags, "rules/trait")
SORT file.mtime DESC
LIMIT 15
```
