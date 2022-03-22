---
title: "Meeting request rule"
typora-root-url: ..\..\..\..\..\static
---

This rule sends an email which includes a meeting request. It is the same as the Send email rule with three additional fields to add the details of the meeting:
* Start time
* End time
* Location


If you are using an email connector, a meeting request will appear in the calendar of the receiver(s).  Otherwise the meeting request will appear as a calendar file (.ics file type) attached to an email.

![Meeting request rule dialog box](/images/MeetingRequest.png)

###### When to use 
You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)
###### How to use
To send a meeting request when the user submits a form:
1. Before adding the rule, add fields to store the start date & time, the end date & time, and the location of the meeting: 
   a. Add a date field to the current form: Click on Controls > Input > Date and drag the field onto the form.  Edit the field by clicking on it and then clicking the pen icon. Change the Title to *Start*.  Change the Name(unique) to *start*.  Set Display format to Date and time. Click OK.
   b. Repeat the last step to add another field called *End*.
   c. Add a text field: Click on Controls > Input > Text and drag the field onto the form.  Edit the field by clicking on it and then clicking the pen icon. Change the Title to *Location*. Change the Name(unique) to *location*.  
2. Select the Submit button.
3. Add a rule > Communications > Meeting request.
4. For the Start time, select the Start field added earlier. 
5. For the End time, select the End field added earlier. 
6. And for the Location, select the Location field added earlier.
7. Continue as for the Send email rule.

###### Notes
None.

