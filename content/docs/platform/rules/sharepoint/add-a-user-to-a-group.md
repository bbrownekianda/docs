---
title: "Add a user to a group"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to add a user into a SharePoint group from within Kianda.

When to use:

This rule should be used when a user within Kianda should be added to SharePoint Group, i.e. a new hire being added to a team group during their onboarding

You can add this rule:

·    to a field

·    to a form

·    to a process (the rule will run on load)

 

How to use:

To add a user to a SharePoint group, the first step is to select the SharePoint data source where the group is located, you will then be presented with two fields “Group title field” & “Username or User ID field”. 

These two fields will be present within the Kianda form (these can be a username & group name field for example) and are used to confirm the user which is to be added and the group they are to be added to Then utilizing the success mapping you can set values from the Kianda form into the user entry within SharePoint. 

 

Once these fields are set you can also set conditions on the rule, further details on conditions can be found here:

 

Finally on success/on error mapping can also be set to populate fields on the form, for further details on success & error mapping please see here:
