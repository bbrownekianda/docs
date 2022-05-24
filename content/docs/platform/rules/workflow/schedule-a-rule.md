---
title: "Schedule a rule"
---

This rule allows you to schedule a rule (or field e.g. a button with rules) to be triggered either immediately or at some point in the future. 

![Schedule a Rule](/images/ScheduleaRule1.png)


## When to use 

You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

## How to use

To schedule a daily reminder:
1. Select Controls > Actions > Button to add a button to the bottom of the form.  Change the title of the button to Reminder.  Go to the field property settings and make the button not visible to the user.  You can add rules to this button that will be triggered daily e.g. send an email.
2. Click on another button e.g. the Submit button.
3. Select Add a rule > Workflow > Schedule a Rule.
4. Under Action, select the new Reminder button as the field to be triggered.
5. Under Schedule, click on Daily.  
6. Set **At** to 09:00 and **Every** to 1.  The Reminder button will be triggered at 9am every day.
7. Click OK.

When the form is submitted, a new scheduled task is created.  You can view all of the scheduled tasks in the system by selecting Administration > Scheduled Tasks and clicking on Show All in the top right hand corner of your screen.

###### Notes
| Schedule    | Options                                                      |
| :---------- | :----------------------------------------------------------- |
| One time    | Select **Time mode** as Absolute or Relative from now.  If *Absolute*, you can select the time using the clock icon and the date using the calendar icon OR you can select a form field (where the date is stored) by clicking on the icon with black discs.  If *Relative from now*, enter the days, hours and minutes directly. |
| Minutes     | Every \<select number of minutes> minutes.                   |
| Hourly      | Minutes of hour \<select number of minutes after the hour> Every \<select number of hours>. |
| Daily       | At \<click on clock icon to select time> Every \<select number of days>.  Tick Week days to exclude Saturday and Sunday. |
| Weekly      | Weekday \<select day> At \<click on clock icon to select time> Every \<select the number of weeks>. |
| Monthly     | Select **Day**, \<select the day> or **The** \<select which day e.g. First Monday>.  At \<click on clock icon to select time> Every \<select number of months>. |
| Immediately | None                                                         |

Note that all of the Schedule options are executed on the server side except the Immediately option.

It is possible to set the schedule rule to expire by ticking **Expire**.  There are three options:
1. By: the rule will expire by the date and time given.  Either select the time using the clock icon and the date using the calendar icon OR select a form field (where the date is stored) by clicking on the icon with black discs.
2. After: the rule will expire after a set number of occurrences.  Select the number of occurrences in the blank field or click on the icon with black discs to choose a field where the number of occurrences is stored.
3. When: add a condition which will cause the rule to expire when it is true.

Select **Make task unique** if you want to prevent a second identical task being created for this instance of the process.

Select **Execute in series** if you want the server-side execution to be in series rather than in parallel.          

