---
title: "Reset permissions"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to reset permissions for a user/group within a SharePoint site/list/item within Kianda.

When to use:

This rule should be used when you wish to alter permissions within Kianda to reflect within SharePoint. 

You can add this rule:

·    to a field

·    to a form

·    to a process (the rule will run on load)

 

How to use:

To set the permissions for a user/group in SharePoint, the first step is to select the SharePoint data source where the user or group is located, you will then be presented with three options. 

The item type is used to confirm what level the permissions are to be set, be it at a site level, list level or item level. 

The site relative URL is used as a reference for where the permissions are to be set. This will be a field within Kianda where you will store the site URL from SharePoint. 

Next, the existing permissions allows you to either append or override the permissions of the user/group within SharePoint, if it is set to add to existing it will append the permissions and if it is set to replace existing it will override the current permissions and only reflect the new permissions assigned via this rule. 

The last step is to set the input mapping which is used to determine what level of permissions the user/group will be assigned. The “User or Group ID” will be a field within Kianda which will have the ID for the user or group in SharePoint which is to be updated. The permission level will then detail what permissions will be assigned to the user/group selected in the input mapping. 

Once these fields are set you can also set conditions on the rule, further details on conditions can be found here:

Finally on success/on error mapping can also be set to populate fields of the form or within the site, for further details on success & error mapping please see here:

Further details on conditions can be found here:

This can then be run on a button which is manually triggered by a user, or automatically on load of the process to update a user’s permissions within SharePoint.
