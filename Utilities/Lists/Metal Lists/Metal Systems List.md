---
tags: [list]
---
```dataview
TABLE  tier AS Tier, type AS Type, points as "System Points"
FROM #Metal AND #System
SORT row.group ASC 
```