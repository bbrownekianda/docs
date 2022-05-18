---
title: "Add a user to a group"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to add a user into a SharePoint group from within Kianda.



### When to use

This rule should be used when a user within Kianda should be added to SharePoint Group,for example, a new hire being added to a team group during their onboarding.

You can add this rule:

- [x] to a field

- [x] to a form 

- [x] to a process (the rule will run on load)

  


### How to use

To add a new SharePoint user, choose an item to attach the rule to, for example a field, such as a Submit button. 

1. Select the **Submit** button, for example.

2. Click on **Add a rule** > **SharePoint** > **Add a user to a group**.

3. Select a SharePoint **data source** from the drop-down list.  

4. Two new fields will appear: 
   For **Group title** field, select the field where the group title is stored for example, a list field.
   For **Username or User Id**, select the field where the Username or User id is stored.

5. The final two sections are optional:

   Under **On success mapping**, click on **Add mapping**. 
   	For **Form Field**, select a field to store the text. 
   	For **Data source field** or text, either enter the text or 
   		select a field where the text is stored.

   Under **On error mapping**, click on **Add mapping**. 
   	For **Form Field**, select a field to store the text. 
   	For **Error message** or text, either enter the text or 
   		select a field where the text is stored.

   For further details on success & error mapping please see here.

6. Click on **OK** when complete.

7. Move the rule in the right-hand pane to change the order of execution.

### Notes

To use this rule, you must have a user predefined in Kianda and in SharePoint. The group must also be predefined in SharePoint. This rule gives the advantage of allowing multiple users to move to SharePoint groups which could be useful for example during restructuring in an organisation, where existing users need to move to other departments/groups. 
