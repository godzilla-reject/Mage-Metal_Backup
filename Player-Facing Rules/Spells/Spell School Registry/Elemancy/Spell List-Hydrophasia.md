---
tags: [elemancy]
---
```dataview
LIST rows.file.link
WHERE School = "Hydrophasia"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```