---
tags: [humaana]
---
```dataview
LIST rows.file.link
WHERE School = "Hemaphoresis"
SORT file.name ASC
GROUP BY rank
```