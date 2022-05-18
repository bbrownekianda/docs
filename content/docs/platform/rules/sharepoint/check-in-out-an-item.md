---
title: "Check in or out an item"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to check in or check out an item within SharePoint from Kianda.

 

### When to use

This rule should be used when a user within Kianda wanted to check in or check out an item from SharePoint

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

 

### How to use

To apply this rule, first choose an item to attach the rule to, for example a field, such as a Submit button. 

1. Select the **Submit** button, for example.

2. Click on **Add a rule** > **SharePoint** > **Check in/out an item**.

3. Select a SharePoint **data source** from the drop-down list.  

4. Select the list where the item is present which is needed to be checked in/out.

5. Next the operation should be selected as to whether it is a check in or a check out.  You should then also select the itemID field from the Kianda form, which will be used to determine which item is being checked in/out. 

6. You can then also select a field which will serve as a check in comment field. 

7. The final two sections are optional:

   Under **On success mapping**, click on **Add mapping**. 
   	For **Form Field**, select a field to store the text. 
   	For **Data source field** or text, either enter the text or 
   		select a field where the text is stored.

   Under **On error mapping**, click on **Add mapping**. 
   	For **Form Field**, select a field to store the text. 
   	For **Error message** or text, either enter the text or 
   		select a field where the text is stored.

   For further details on success & error mapping please see here.

8. Click on **OK** when complete.

9. Move the rule in the right-hand pane to change the order of execution.
