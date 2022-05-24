---
title: "Validate input"
---



The **Validate input** provides the ability to perform flexible data validation and prevents incorrect data submission. This could be performed for example on a date of birth field, where the validation checks that the person submitting a form is over 18 years of age. 

### When to use

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)



### How to use

To implement the rule:

1. Select a field to attach the rule to.
2. Click on **Add a rule** > **Form actions** > **Validate input**. 
3. In the **Edit rule - Validate input** dialog box, give the rule a **Title**. 
4. Create validation conditions for the action to happen, see [Conditions](/docs/platform/rules/general/add-conditions/) for more information.
5. Under Action, type in a message for the user under **Error message to display when rule conditions above apply** if you want to allow background upload of forms or chunked upload of forms. 

6. Under Action, you can also check the box for **Perform partial save** to allow partial save of a form. 
7. Select a form or field to **Trigger rules if validation condition apply** so that rules attached to that particular form or field are initiated if the condition(s) set in step 4 apply.