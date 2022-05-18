---
title: "Create a group"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to create a SharePoint group from within Kianda.

### When to use

This rule should be used when you want to create a new SharePoint group from within your Kianda process for example as part of a new project you want to create a group in SharePoint to provide permissions to specific users.

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

 
### How to use

To apply this rule, first choose an item to attach the rule to, for example a field, such as a Submit button. 

1. Select the **Submit** button, for example.

2. Click on **Add a rule** > **SharePoint** > **Create a group**.

3. Select a SharePoint **data source** where you want the group to be located. 

4. Two new fields will appear to allow you to confirm group details: 
   For **Group title** field, select the field where the group title is stored for example,  a list field.
   For **Group Description field**, create a description for the group. 
5. The final two sections are optional:

Under **On success mapping**, click on **Add mapping**. 
	For **Form Field**, select a field to store the text. 
	For **Data source field** or text, either enter the text or 
		select a field where the text is stored.

Under **On error mapping**, click on **Add mapping**. 
	For **Form Field**, select a field to store the text. 
	For **Error message** or text, either enter the text or 
		select a field where the text is stored.

6. Click on **OK** when complete.

7. Move the rule in the right-hand pane to change the order of execution.
