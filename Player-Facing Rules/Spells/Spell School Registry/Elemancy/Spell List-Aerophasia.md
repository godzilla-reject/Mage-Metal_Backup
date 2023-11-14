---
tags: [elemancy]
---
```dataview
LIST rows.file.link
WHERE School = "Aerophasia"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```