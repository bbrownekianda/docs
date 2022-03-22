###### Examples using multiple rules
**To add a row to a table in real-time:**
In this example, the user can add rows to a table in real-time.  The user opens the form, enters a value in a field and that number of rows will be added to the table. 

![Add rows to table example](images/multiplerules_addrowstotable.png)

Rules used:
- [x] Set form field
- [x] Schedule a rule
- [x] Add table row

Add the fields:

1. Before adding the rule, add two Number fields: Click on Controls > Input > Number and drag the field onto the form. Edit the field by clicking on it and then clicking the pen icon. Change the Title of the field to **Total**.  Change the Name(unique)  to total. Repeat for another field called **Count**.  In the Count field, enter the initial value as 0.
2. Before adding the next rule, add a table: Click on Controls > Input > Table and drag the table onto the form. Edit the Table by clicking on it and then clicking the pen icon. Change the Title of the field to **Table**.  Change the Name(unique)  to table. Set Enable adding rows to No and set Add first row onload to No. 

Use the Set form field rule:

1. Select the Total field and Add a rule > Data > Set form field.  
2. Change the title to Increment Count.
3. Click on Edit Conditions. 
   - Click on Add a conditions group.  On the left, select the Count field.  
   - From the drop down menu, select Less than.  On the right, select the Total field.
   - Click OK.
4. Under Form field to set, select the Count field.
5. Under Value or expression, open the Expression builder by clicking on the button with 3 black dots.
6. In the Expression builder:
   - Under Add field to expression, select the Count field.  Click on Add to Expression. 
   - In the Expression window, enter the '+ 1' symbol.
   - Click OK.
7. Under Value or expression, check the expression is [Count] + 1.
8. Click OK.

Use Schedule a rule:

1. Select the Count field and Add a rule > Workflow > Schedule a rule. 
2. Change the title to Loop.
3. Under Action, Select the Total field.  
4. Select Immediately and click OK.

Use the Add table row rule:

1. Select the Count field and Add a rule > Tables > Add table row.
2. Under Action, select the Table.
3. Under Table row field, select row1 > Text1.
4. Under Form field or text, select the Count field.
5. Click OK.
6. Move this rule to run before Loop (Schedule a rule).  It should appear first in the list of rules.

Test by saving and running in the Previewer.  Type a value in the Total field and hit Return.  That number of rows will be added to the table.

