---
title: "Start a process"
---

This rule allows you to start a new instance of a different process (or a new instance of the same process). You can transfer field data from the current process instance to a new process instance. 

![Process security rule dialog box 1](/images/StartaProcess.png)

## When to use 

You can add this rule:
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

## How to use

To start an instance of a the Sample Process from the current process:
1. Click on a button e.g. the Submit button.
2. Select Add a rule >Workflow > Start a Process.
3. Under Action, select Own process.
4. Choose a target process design e.g. Sample Process.  
5. Under Input mapping, click on Add mapping.  On the left side, choose a field from the current process.  On the right side, select a destination field in the target process.
6. Click On success mapping. On the right side, type a message;  on the left side, choose a field to store the message.  Here data is being mapped back from the target process to the current process.
7. Click OK.

## Notes

The target process can be a **Partner process**.  The partner organisation must have enabled process security (in the Process settings for the target process) to allow your process to interact with the target process.

Use the **Lookup existing process** flag to find a particular instance of the target process at runtime.  If you select Yes, then you can select a field in the current process which contains the id of the target instance.

**Table mapping** allows you copy the contents of a table in the current process to a table in the target process.  Click on Table mapping.  On the right side, select a table in the current process;  on the left side, choose a table in the target process.  Click on the three dots icon to set the table mappings. If you select Copy rows and click on Copy row conditions you can control which rows are copied over to the target process.  If you select Update rows and click on Update row conditions, then you can control which rows are updated with new data.

Use **Trigger rules in target instance** to select a field or rule to trigger in the target process.  Set Execute in series to Yes to ensure server side execution is performed in series instead of in parallel.  

Another feature of this rule is that you can **read data from another process** instance.  In this case it is advisable to give the title of the rule a title such as Read data from Process X.  Here you click On success mapping and use this area to copy data from the target process to the current process.

