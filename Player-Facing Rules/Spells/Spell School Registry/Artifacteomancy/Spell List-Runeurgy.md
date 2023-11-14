---
tags: [artifacteomancy]
---
```dataview
LIST rows.file.link
WHERE School = "Runeurgy"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```