---
title: "Delete data item rule"
linkTitle: "Delete item"
typora-root-url: ..\..\..\..\..\static
---

This rule works exactly like Update item rule. To delete an item from your data connection, you could use a data source filter and map data source field or text from a data connection to Kianda form field.
Delete an item in a data source	"Datasource query rule - Use this rule together with a datasource to perform a delete query and return data identifiers for use with the form. Employ the transactional nature of the rule fields, results and error nodes to build retry logic" 

![Delete item dialog box](/images/deleteitem.png)

###### When to use 
You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

###### How to use
To ..SharePoint list:???
1. Click on a button e.g. the Submit button.???
2. Select Add a rule > Data >Delete item.
3. Under Action, click on Select data source.
- Select a SharePoint??
4. Data source filter
5. Under On success mapping...
6. Under On error mapping...

###### Notes

