---
tags: [elemancy]
---
```dataview
LIST rows.file.link
WHERE School = "Metallomancy"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```