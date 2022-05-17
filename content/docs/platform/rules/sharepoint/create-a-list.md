---
title: "Create a list"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to create a SharePoint List from within Kianda.

When to use:

This rule should be used when within your Kianda process you wish to create a new SharePoint List, i.e. as part of a new project you want to create a list in SharePoint to store information pertaining to that project.

You can add this rule:

·    to a field

·    to a form

·    to a process (the rule will run on load)

 

How to use:

To create a SharePoint list, the first step is to select the SharePoint data source where you want the list to be located, you will then be presented with six options. 

The List template allows you to select an existing SharePoint list within the SharePoint data source to emulate the formatting and design of the list.

List Name, List URL, and List description field are all derived from the Kianda form. Here you select a Kianda field which will be used as the base for the list you are creating. The name field will be used to create the name of the list, the list URL will be used in the creation of the URL within SharePoint and finally the List description will be used for the SharePoint list description.

Once these fields are set you can also set conditions on the rule, further details on conditions can be found here:

Finally on success/on error mapping can also be set to populate fields of the form or within the List, for further details on success & error mapping please see here:
