---
title: "Remove a user from a group"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to remove a user from a SharePoint group from within Kianda.

### When to use

This rule should be used when a user within Kianda should be removed from a SharePoint Group, i.e. an employee leaving a company and to ensure they are removed from team groups

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

 

### How to use

To apply this rule, first choose an item to attach the rule to, for example a field, such as a Submit button. 

1. Select the **Submit** button, for example.

2. Click on **Add a rule** > **SharePoint** > **Remove a user from a group**.

3.  Select the SharePoint data source where the group is located.

4. Two new fields will appear: **Username** and **Group name**. These are used to confirm the user which is to be removed and the group they are to be removed from. 
   For **Group title** field, select the field where the group title is stored for example, a list field.
   For **Username or User Id**, select the field where the Username or User id is stored.

5. Once these fields are set you can also set conditions on the rule, further details on conditions can be found here.

6. The final two sections are optional:

   Under **On success mapping**, click on **Add mapping**. 
      	For **Form Field**, select a field to store the text. 
      	For **Data source field** or text, either enter the text or 
      		select a field where the text is stored.

      Under **On error mapping**, click on **Add mapping**. 
      	For **Form Field**, select a field to store the text. 
      	For **Error message** or text, either enter the text or 
      		select a field where the text is stored.

7. Click on **OK** when complete.

8. Move the rule in the right-hand pane to change the order of execution.

   

