---
tags: [elemancy]
---
```dataview
LIST rows.file.link
WHERE School = "Terraphasia"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```