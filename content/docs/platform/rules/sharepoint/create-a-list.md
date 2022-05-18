---
title: "Create a list"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to create a SharePoint List from within Kianda.

### When to use

This rule should be used when within your Kianda process you wish to create a new SharePoint list, for example as part of a new project you want to create a list in SharePoint to store information pertaining to that project such as invoice numbers.

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)


### How to use

To apply this rule, first choose an item to attach the rule to, for example a field, such as a Submit button. 

1. Select the **Submit** button, for example.

2. Click on **Add a rule** > **SharePoint** > **Create a list**.

3. Select a SharePoint **data source** where you want the list to be located. You will be presented with <u>six options</u>.

4. The List template allows you to select an existing SharePoint list within the SharePoint data source to emulate the formatting and design of the list. List Name, List URL, and List description field are all derived from the Kianda form. Here you select a Kianda field which will be used as the base for the list you are creating. The name field will be used to create the name of the list, the list URL will be used in the creation of the URL within SharePoint and finally the List description will be used for the SharePoint list description.

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

6. Click on **OK** when complete.

7. Move the rule in the right-hand pane to change the order of execution.
