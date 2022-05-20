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

To apply this rule, first choose an item to attach the rule to and have a SharePoint data source ready where you want the list to be located. This data source should be a predefined data connector created with **Data sources** under **Administration**. 

1. Select the field or other item to attach the rule to.
2. Click on **Add a rule** > **SharePoint** > **Get attachments**.
3.  In the **Edit rule - Get attachments** dialog box, give the rule a **Title**. Then select a SharePoint data source by clicking on **Select data source**.
	  ![Get attachments dialog box](/images/get-attachments-rule.jpg)
4. Click on **Data source filter** to create a filter to find that data source.
5. For the field **Select a destination file input** select the file field within Kianda where the file should be available.
6. Once these fields are set, you can set a condition on the rule to determine which file is pulled from SharePoint. The simplest way of doing this is to use a condition on the name of the attachment within SharePoint that equals a value that is set on the condition, for example, “filename.csv”.
7. Click on **OK** when complete.

This rule can then be run for example on a button which is manually triggered by a user, or automatically on load of the process. From here the file can be utilized to populate data fields, tables and so on. This will be discussed further in <u>other rules</u>. 




### User tip ![Target icon](/images/05.png) ###

If you have multiple rules attached to the field or other item, you may wish to reorder the rules to change the order of rule execution. Go to [Multiple rules](/docs/platform/rules/general/multiple-rules/)  to find out more. 




### What's next  ![Idea icon](/images/18.png) ###

Now that you've learned about **Get attachments**, return to the [SharePoint rules](/docs/platform/rules/SharePoint/) page to find out about other SharePoint rules. 
