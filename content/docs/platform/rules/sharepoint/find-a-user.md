---
title: "Find a user"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to find a user from a data source using a Kianda process.

### When to use

Use this rule to pull user data into a Kianda form for example when someone wants to add employee information to a form using SharePoint details.

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

 

### How to use

To apply this rule, first choose an item to attach the rule to and have a SharePoint data source ready where you want the list to be located. This data source should be a predefined data connector created with **Data sources** under **Administration**. 

1. Select a field or other item to attach the rule to.

2. Click on **Add a rule** > **SharePoint** > **Find a user**.

3. In the **Edit rule - Find a user** dialog box, give the rule a **Title**. Then select a SharePoint data source from the drop-down list.

4. 
  ![Find a user dialog box](/images/find-a-user-rule.jpg)

5. You will be presented with two options within the dialog box:

  - **Find user by** provides the search criteria to find the user that is, **display name**, **email**, or **ID**. 
  - **Search term field** is used to select the Kianda form field which will be used to lookup the user details from the data source. 

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

8. Move the rule in the right-hand pane to change the order of execution as necessary.



### What's next  ![Idea icon](/../content/docs/platform/rules/sharepoint/find-a-user.assets/18.png) ###

Now that you've learned about **Find a user**, return to the [SharePoint rules](/docs/platform/rules/sharepoint/) page to find out about other SharePoint rules. 
