---
title: "Create a site"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to create a SharePoint site from within Kianda.

### When to use

This rule should be used when within your Kianda process you wish to create a new SharePoint site, for example, as part of a new project you want to create a site in SharePoint to store information pertaining to that project, to include all lists and other documentation that you need. 

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

 

### How to use

To apply this rule, first choose an item to attach the rule to, for example a field, such as a Submit button. 

1. Select the **Submit** button, for example.
2. Click on **Add a rule** > **SharePoint** > **Create a site**.
3. Select a SharePoint **data source** where you want the group to be located. You will be presented with <u>six options</u>.
4. The site template allows you to select an existing SharePoint site within the SharePoint data source to emulate the formatting and design of the site Site Name, site URL, and site description field are all derived from the Kianda form. Here you select a Kianda field which will be used as the base for the site you are creating. The name field will be used to create the name of the site, the site URL will be used in the creation of the URL within SharePoint and then the site description will be used for the SharePoint site description. Additionally, you can enable “Inherit parent permissions” which will allow you to new site to inherit parent permissions for the SharePoint location.
5. Once these fields are set you can also set conditions on the rule, further details on conditions can be found here.
6. The final two sections are optional:

Under **On success mapping**, click on **Add mapping**. 
	For **Form Field**, select a field to store the text. 
	For **Data source field** or text, either enter the text or 
		select a field where the text is stored.

Under **On error mapping**, click on **Add mapping**. 
	For **Form Field**, select a field to store the text. 
	For **Error message** or text, either enter the text or 
		select a field where the text is stored.

6. Click on **OK** when complete.

7. Move the rule in the right-hand pane to change the order of execution.
