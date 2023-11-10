---
tags: [list]
---
```dataview
LIST rows.file.link
FROM #Trait
SORT file.name ASC
GROUP BY category
```