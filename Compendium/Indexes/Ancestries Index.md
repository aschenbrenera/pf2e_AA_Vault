---
tags:
  - index
format: 2.0
source: Player Core
---

# Ancestries Index

```dataview  
TABLE WITHOUT ID link(file.name) AS "Ancestry", size AS "Size", hp AS "HP", speed AS "Speed", attributes AS "Attributes", other AS "Other"
FROM "Compendium/Ancestries"
SORT file.name
```
