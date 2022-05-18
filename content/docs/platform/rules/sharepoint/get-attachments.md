---
title: "Get List item attachments"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to retrieve an <u>attachment</u> from a SharePoint list for use in a Kianda process.

### When to use

This rule should be used when an attachment is to be pulled from SharePoint and displayed within a Kianda process.

You can add this rule:

- [x] to a field

- [x] to a form 

- [x] to a process (the rule will run on load)

  


### How to use

To apply this rule, first choose an item to attach the rule to, for example a field, such as a Submit button or other button.

1. Select the field to attach the rule to.
2. Click on **Add a rule** > **SharePoint** > **Get attachments**.
3. Select a SharePoint **data source** where the file is located. Then select the file field within Kianda where the file should be available.
4. Once the <u>setup is complete</u>, you can set a condition on the rule to determine which file is pulled from SharePoint. The simplest way of doing this is to use a condition on the name of the attachment within SharePoint equaling a value that is set on the condition, i.e. “filename.csv”.

This rule can then be run on a button which is manually triggered by a user, or automatically on load of the process. From here the file can be utilized to populate data fields/tables etc. This will be discussed further in <u>other rules</u>. 



### What's next  ![Idea icon](/../content/docs/platform/rules/sharepoint/get-attachments.assets/18.png) ###

Now that you've learned about **Get attachments**, return to the [SharePoint rules](/docs/platform/rules/SharePoint/) page to find out about other SharePoint rules. 
