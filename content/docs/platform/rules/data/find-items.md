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

This rule is used to find an item from your data-connections. To find an item, you could use a data source filter which acts as a conditional bridge between Kianda and data-connections. If the condition is true, you could map the data source field or text to the Kianda form field.???

This rule is used to perform a query and return data for use in the form.  The data may be stored locally or in one of the data sources.???


Datasource query rule - Use this rule together with a datasource to perform a query and return data for use with the form. Employ the datasource filter when using databases and the transactional nature of the rule to build retry logic	???
FROM HELP???
The Data source filter is excellent when you want to query data from a specific user using a unique identifier like an Id, name or email, for example.???

![Find items dialog box](/images/finditems.png)

###### When to use 
You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

###### How to use

To read in data from a SharePoint list:
1. Click on a button e.g. the Submit button.
2. Select Add a rule > Data > Find items.
3. Under Action, click on Select data source.
- Select a SharePoint list e.g. Cities.
4. Under Results Mapping...

To filter data in a SharePoint list:???see 5:34 mins
1. Button?
2. Select Add a rule > Data > Find items.
3. Click on the rule that has the data you want to filter.
4. Click on the Data source filter button.
5. Choose the appropriate condition - in this case, we used the Id.
6. Click 'OK'.

To make a remote procedure call
1. Click on a button e.g. the Submit button.
2. Select Add a rule > Data > Find items.
3. Under Action, click on Select data source.
- Select a REST Service e.g. Cities.
4. ??where of SQL??? Data source filter
5. Under Input Mapping, specify the columns that will be retrieved.
SQL statement: SELECT top 100 [name], [MatDesc] From Materials where PlatCode = 100 order by asc

###### Notes
1. Data sources that can be used:
- SQL databases
- SharePoint lists
- etc.

2. Remote procedure data
- SAP BAPIs
- REST Endpoints

Key difference between 1 and 2 is input mapping parameters versus data source filtering

On error mapping: 
- Max rows: allows you to further limit the amount of data that you are retrieving from the data source.  Set the maximum number of rows.
- Sort By and Direction enable sorting of the data.
- Enable offline cache: If set to Yes, the data will be available when the user is offline.  It should be used for small data sets (less than 500 rows).


These data rules are transactional rules - e.g. find items 
success 
failure
You can build in re-try logic
If you cannot connect to a database and that throws an error, that error can be trapped inside a variable or field and that same transaction can be run again later or even notify the user that the data is not available 
text from error message is from the data source that you are using

