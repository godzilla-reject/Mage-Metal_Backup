---
Tags:
Category:
Completed: 
---
<% await tp.file.move("/General Rules/Traits Catalog/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewTrait");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Trait Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox|left]+ Trait Entry
> # `=this.file.name`
> ###### Trait Information
> 