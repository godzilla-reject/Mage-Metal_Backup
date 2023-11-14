---
tags: []
---
```dataview
LIST rows.file.link
WHERE School = "{{SchoolHere}}"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```