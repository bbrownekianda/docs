---
title: "Compare dates"
---

The compare dates rule is utilised to compare two date fields and store the difference between them in a Kianda form field.

### When to use

This rule should be used when a user wishes to compare one date with another from within Kianda.

You can add this rule:

- [x] to a field

- [x] to a form 

- [x] to a process (the rule will run on load)

### How to use
To apply this rule, first choose an item to attach the rule to.

1. Click on **Add a rule** > **Dates** > **Compare dates**.
2. The Compare dates rule dialog box appears. Give the rule a Title.
     ![Compare dates dialog box](/images/compare-dates.jpg)
3. Under **Date to compare**, select the date to compare where the calculation will start from. 
4. Under **Compare function** select from the options: **Is between dates**, **Is before date**, and **Is after date**. If you choose a) **Is between dates** then you must provide the **Compare from date** and **Compare to date**. If you choose b) or c) then you need only to provide the **Compare to date**. These are fields from within the Kianda form.
5. Under **Result**, select a **Destination field** which is the new date to store the comparison. 
6. You then need to select what unit the time is, whether it is a minute, hour, day, etc. 
7. Then you select when the date is to be compared to i.e., a date field, today, or now. 
8. You must then select the date field within the destination field which this new date is to be stored within. You can also select if it is business hours so the time is set to within your working hours.
9. You can also count only full minutes via a yes/no option, so the resulted time will be a rounded to the minute. 

Finally, you can decide to exclude weekends or special dates within your date calculation, using the date calculation settings & the special date settings. 
