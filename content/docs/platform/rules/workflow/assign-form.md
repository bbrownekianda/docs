---
title: "Assign form"
---

This rule is used to assign a form to a user or to a group of users.  You can override the existing users or add to the existing users.

![Assign rule dialog box](/images/Assign.png)

## When to use 
You can add this rule:
- [x] to a field
- [x] to a form
- [x] to a process (the rule will run on load)

## How to use
To assign a form to a user:
1. Select Controls > Input > User picker to add a field to store the user.
2. Click on a button e.g. the Submit button.
3. Select Add a rule > Workflow > Assign form.
4. Under Action, select a form.  You can select more forms by clicking the plus icon.
5. For Assign to, select Defined in a user field. Then select the User picker field created earlier.
6. Set Existing user(s) to Override to make the selected user the only user.  
7. Click OK.

## Notes
This rule can be used multiple times in sequence: typically the first rule overrides the existing users and the following rule(s) appends users.

To view the default owners for the form, go to Edit form in the Designer.













