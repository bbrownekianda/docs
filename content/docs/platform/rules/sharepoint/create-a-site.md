---
title: "Create a site"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to create a SharePoint site from within Kianda.

When to use:

This rule should be used when within your Kianda process you wish to create a new SharePoint site, i.e. as part of a new project you want to create a site in SharePoint to store information pertaining to that project.

You can add this rule:

·    to a field

·    to a form

·    to a process (the rule will run on load)

 

How to use:

To create a SharePoint site, the first step is to select the SharePoint data source where you want the site to be located, you will then be presented with six options. 

The site template allows you to select an existing SharePoint site within the SharePoint data source to emulate the formatting and design of the site.

site Name, site URL, and site description field are all derived from the Kianda form. Here you select a Kianda field which will be used as the base for the site you are creating. The name field will be used to create the name of the site, the site URL will be used in the creation of the URL within SharePoint and then the site description will be used for the SharePoint site description. Additionally, you can enable “Inherit parent permissions” which will allow you to new site to inherit parent permissions for the SharePoint location

Once these fields are set you can also set conditions on the rule, further details on conditions can be found here:

Finally on success/on error mapping can also be set to populate fields of the form or within the site, for further details on success & error mapping please see here:
