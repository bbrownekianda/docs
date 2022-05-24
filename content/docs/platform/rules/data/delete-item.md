---
title: "Delete data item rule"
linkTitle: "Delete item"
typora-root-url: ..\..\..\..\..\static
---

This rule works exactly like Update item rule. To delete an item from your data connection, you could use a data source filter and map data source field or text from a data connection to Kianda form field.
Use this rule together with a datasource to perform a delete query and return data identifiers for use with the form. Employ the transactional nature of the rule fields, results and error nodes to build retry logic" 

![Delete item dialog box](/images/deleteitem.png)

### When to use 
You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

### How to use
1. Click on a button e.g. the Submit button.
2. Select Add a rule > Data >Delete item.
3. Under Action, click on Select data source, for example a SharePoint data connector.
4. Under **On success mapping** select the field(s) in the form which will store information and populate the **data source field or text** field with the respective data source value. 
5. Under **On error mapping** select the field(s) in the form which will store error messages. Then type in a value or use Error message, to create a system generated error message if an error occurs during rule execution.

