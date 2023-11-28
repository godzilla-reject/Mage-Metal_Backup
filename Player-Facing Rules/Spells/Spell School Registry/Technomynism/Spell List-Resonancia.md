---
tags: technomynism
---
```dataview
LIST rows.file.link
WHERE School = "Resonancia"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```