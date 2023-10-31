---
tags: []
---
```dataview
LIST rows.file.link
WHERE School = "{{SchoolHere}}"
SORT file.name ASC
GROUP BY rank
```