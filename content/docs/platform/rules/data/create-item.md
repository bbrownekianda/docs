---
title: "Create data item rule"
linkTitle: "Create item"
typora-root-url: ..\..\..\..\..\static
---

This  rule is used to create an item on your data-connection. This is a straight forward rule which allows you to connect to your data source and map inputs. Also, you could map a data source field or text back to Kianda on success or store an error message on failure.

Sharepoint or SQL Server

![Create item dialog box](/images/createitem.png)

### When to use 
You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

### How to use
1. Click on a button e.g. the Submit button.
2. Select **Add a rule** > **Data** >**Create item**.
3. Under Action, click on **Select data source**, for example the data source could be a SharePoint data connector.
4. Under **Input mapping** select the fields in the form that will map to SharePoint fields, such as User ID.
5. Under **On success mapping** select the field(s) in the form which will store information and populate the **data source field or text** field with the respective data source value. 
6. Under **On error mapping** select the field(s) in the form which will store error messages. Then type in a value or use Error message, to create a system generated error message if an error occurs during rule execution.



