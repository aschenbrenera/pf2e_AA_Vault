---
tags:
  - index
format: 2.0
source: Player Core
---

# Deities Index

```dataview  
TABLE WITHOUT ID link(file.name) AS "Deity", sanctification AS "Sanctification", attributes AS "Divine Attributes", skill AS "Divine Skill", domains AS "Domains"
FROM "Compendium/Deities"
SORT file.name
```