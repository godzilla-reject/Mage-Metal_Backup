---
tags: [artifacteomancy]
---
```dataview
LIST rows.file.link
WHERE School = "Glyphiamancy"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```