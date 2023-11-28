---
tags: 
---
```dataview
LIST rows.file.link
WHERE School = <%* let School = await tp.system.prompt("Enter the Spell School") _%> <% School %>
WHERE Completed = true
SORT file.name ASC
GROUP BY rank
```
<% await tp.file.rename("Spell List-" + School) %>