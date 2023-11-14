---
tags: [elemancy]
---

```dataview
LIST rows.file.link
WHERE School = "Electromancy"
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```