---
tags:
  - index
format: 1_0
---
# Activities, Exploration Core Focus Index

These are the exploration core focus activities. These activities have a discrete focus, objective, and duration. These activities are mostly used when staying in the same location.
```dataview  
LIST
WHERE contains(tags, "activity_exploration/core")
AND !contains(tags, "custom_group/exploration_tactic")
SORT file.name
```
