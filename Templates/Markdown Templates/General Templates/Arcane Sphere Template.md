
- - -
<%* let thisSphere = await tp.system.prompt("Enter the Sphere's Name.") _%>  
# Access 
# Schools
```dataview
LIST rows.file.link
FROM #<% thisSphere %> 
SORT file.name ASC
```
<% await tp.file.rename("Arcane Sphere-" + thisSphere) %>