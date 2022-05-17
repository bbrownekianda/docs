---
title: "Create a group"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to create a SharePoint group from within Kianda.

When to use:

This rule should be used when within your Kianda process you wish to create a new SharePoint group, i.e. as part of a new project you want to create a group in SharePoint to provide permissions to specific users

You can add this rule:

·    to a field

·    to a form

·    to a process (the rule will run on load)

 

How to use:

To create a SharePoint group, the first step is to select the SharePoint data source where you want the group to be located, you will then be presented with two fields “Group title field” & “Group Description field”. 

These two fields will be present within the Kianda form (these can be a group description & group name field for example) and are used to confirm the group details. Then utilizing the success mapping you can set values from the Kianda form into the group details within SharePoint. 

Once these fields are set you can also set conditions on the rule, further details on conditions can be found here:

Finally on success/on error mapping can also be set to populate fields of the form or within the List, for further details on success & error mapping please see here:
