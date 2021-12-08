##### Create item
###### Introduction
This  rule is used to create an item on your data-connection. This is a straight forward rule which allows you to connect to your data source and map inputs. Also, you could map a data source field or text back to Kianda on success or store an error message on failure.

Sharepoint or SQL Server

![Create item dialog box](images/createitem.png)

###### When to use 
You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

###### How to use
To ..SharePoint list:???
1. Click on a button e.g. the Submit button.???
2. Select Add a rule > Data >Create item.
3. Under Action, click on Select data source.
- Select a SharePoint??
4. Under Input mapping...
5. Under On success mapping...
6. Under On error mapping...


###### Notes
Explain other advanced scenarios of the rule

Create an item in a data source	"Datasource query rule - Use this rule together with a datasource to perform a create / insert query and return data identifiers for use with the form. Employ the transactional nature of the rule with input fields, results and error nodes to build retry logic"	
 FROM HELP??
 It's easy! First, make sure you have Kianda Cloud Connect installed on your computer (refer to How to download Kianda Cloud Connect, in the help section), and you have successfully configured a connection to your on-premises SQL database (refer to Can I connect to an on-premises data source?).

On the example, we already have these set, and also, we have a SQL database with a table called Products, as well as a form with the same name and fields.

To save the data into the SQL database, you use the same method as in any other data source:

Add the Create Item rule (under Data) on the button of your choice
Click on Select Data Source, and select your Connection
Map your input according to the database


