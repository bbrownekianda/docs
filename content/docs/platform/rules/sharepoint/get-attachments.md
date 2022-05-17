---
title: "Get List item attachments"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to retrieve an attachment from a SharePoint list and become available within Kianda 

When to use:

This rule should be used when an attachment is to be pulled from SharePoint and displayed within a Kianda process.

You can add this rule:

·    to a field

·    to a form

·    to a process (the rule will run on load)

 

How to use:

To retrieve an attachment from SharePoint, the first step is to select the SharePoint data source where the file is located, you will then select the file field within Kianda where the file should be available. 

Once the setup is complete, you can set a condition on the rule to determine which file is pulled from SharePoint. The simplest way of doing this is to use a condition on the name of the attachment within SharePoint equaling a value that is set on the condition, i.e. “filename.csv”.

Further details on conditions can be found here:

This can then be run on a button which is manually triggered by a user, or automatically on load of the process. From here the file can be utilized to populate data fields/tables etc. This will be discussed further in other rules. 
