```dataview
LIST rows.file.link
FROM #Equipment
SORT completed ASC
GROUP BY type
```