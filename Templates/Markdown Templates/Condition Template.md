<% await tp.file.move("/General Rules/Conditions Catalog/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewCondition");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Condition Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox|left]+ Condition Entry
> # `=this.file.name`
> ###### Condition Information
> Category: `=this.Category`
> 
> ######  *Stage One*