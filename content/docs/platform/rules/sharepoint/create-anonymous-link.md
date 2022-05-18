---
title: "Create an anonymous link"
typora-root-url: ..\..\..\..\..\static
---

This rule allows you to create an anonymous link for a file within SharePoint from a Kianda form

### When to use

This rule should be used when a file within SharePoint should be shared with an individual via an anonymous link.

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)


### How to use

To apply this rule, first choose an item to attach the rule to, for example a file field where the desired file is set in Kianda.

1. Select a file field.
2. Click on **Add a rule** > **SharePoint** > **Create anonymous link**.
3. Select a SharePoint **data source** where you want the group to be located.
4. The next step is to set the <u>duration of the link</u>, this is by default 6 hours, this can be extended or reduced as needed. 
5. Finally, choose a field within Kianda to store this <u>anonymous link</u>, which can then be used to access the file. For example you could create a utility panel with a textbox for the anonymous link, where the panel and the textbox are not visible to users. This textbox is simply used to hold the system generated link.
