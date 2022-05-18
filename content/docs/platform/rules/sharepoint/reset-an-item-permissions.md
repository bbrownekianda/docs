---
title: "Reset permissions"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to reset permissions for a user/group within a SharePoint site/list/item within Kianda.

### When to use

This rule should be used when you wish to alter permissions within Kianda to reflect within SharePoint. 

You can add this rule:

- [x] to a field

- [x] to a form 

- [x] to a process (the rule will run on load)

 

### How to use

To add a new SharePoint user, choose an item to attach the rule to, for example a field, such as a Submit button. 

1. Select the **Submit** button, for example.
2. Click on **Add a rule** > **SharePoint** > **Add a user to a group**.
3. Select a SharePoint **data source** from the drop-down list where the user or group is located. You will be presented with three options:
   - The **item type** is used to confirm what level the permissions are to be set, be it at a site level, list level or item level. Choose from the options: **Site**, **List** or **Other item**. 
   - The **site relative URL** is used as a reference for where the permissions are to be set. This will be a field within Kianda where you will store the site URL from SharePoint. Copy in the URL of the SharePoint item. You can also sore the URL in a field and select the field from the <u>drop-down list</u>.
   - The **Existing permissions** allows you to either append or override the permissions of the user/group within SharePoint. Choose from the options: **Add to existing** or **Replace existing**. If it is set to **Add to existing** it will append the permissions and if it is set to **Replace existing** it will override the current permissions and only reflect the new permissions assigned via this rule. 
4. Under **Input mapping** section, click on **Add mapping**. This setting is used to determine what level of permissions the user/group will be assigned.
   For **User or Group id**, select the field where the user is stored.  This could be either a  User Picker field or a text field.
   Select the **Permission level** from the drop-down list.  Examples are <u>**Edit** or **View only**</u>.
5. Once these fields are set you can also set conditions on the rule, further details on conditions can be found here:
6. The final two sections are optional:

​	Under **On success mapping**, click on **Add mapping**. 
​	For **Form Field**, select a field to store the text. 
​	For **Data source field** or text, either enter the text or 
​		select a field where the text is stored.

​	Under **On error mapping**, click on **Add mapping**. 
​	For **Form Field**, select a field to store the text. 
​	For **Error message** or text, either enter the text or 
​		select a field where the text is stored.

7. Click on **OK** when complete.
8. Move the rule in the right-hand pane to change the order of execution.
