---
title: "Find items data rule"
linkTitle: "Find items"
typora-root-url: ..\..\..\..\..\static
---

This rule implements the Read function which is one of the four CRUD functions.  The rule will read one or more items of data from a chosen data source (see notes below on the types of data source that can be used).

| Rule        | CRUD function |
| :---------- | :------------ |
| Find items  | Read          |
| Create item | Create        |
| Update item | Update        |
| Delete item | Delete        |

This rule is used to find an item from your data-connections. To find an item, you could use a data source filter which acts as a conditional bridge between Kianda and data-connections. If the condition is true, you could map the data source field or text to the Kianda form field.

This rule is used to perform a query and return data for use in the form.  The data may be stored locally or in one of the data sources

The Data source filter is useful when you want to query data from a specific user using a unique identifier like an Id, name or email.

![Find items dialog box](/images/finditems.png)

###### When to use 
You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

###### How to use

To read in data from a SharePoint list:
1. Click on a button for example the Submit button.
2. Select **Add a rule** > **Data** > **Find items**.
3. Under Action, click on **Select data source**, for example select a SharePoint list.
4. Under Results Mapping, select a **data source field or text**. In a SharePoint list example, this could be any number of SharePoint values like ID, Created By or Version. This field will then map to a **form field** by selecting the respective field in the form.
4. Under Error mapping, select the **max rows** that you want to appear, and choose a data source value to **Sort by**.




