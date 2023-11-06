---
type: <%* let myChoice = await tp.system.prompt("Enter the Equipment's Type") _%> <% myChoice %>
---
<%* if (myChoice == "Shield") { %>
<% tp.file.include("[[Shield Template]]") -%>
<%* } else { %>
<% tp.file.include("[[Equipment Template]]") -%>
<%* } %>