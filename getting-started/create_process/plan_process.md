# Plan your process

Currently you may have paper forms or email flows that you want to formalise, digitise and most importantly, link to dashboards to see at a glance how processes are running and where organisational improvements are needed.

For example take the scenario of a Training Request. An employee may email a line manager requesting to attend training. The line manager either approves or disapproves the request by returning an email or calling the employee. If the training request is approved then the line manager emails the training manager stating that the employee will attend training and to schedule this.

![Email trail](../images/emails.png)



Rather than continuing with email trails, with no easy way to see the status of each step and process overall, creating a solution in Kianda will save time, increase efficiencies and therefore reduce costs. In this way you are becoming a **citizen developer**, a business professional who uses low-code/no-code tools to solve business needs. 



## Planning in an agile way

Planning involves 3 considerations: [**Design**](#planning-your-design) , [**Interaction**](#planning-interaction)  and [**Management**](#planning-management) explained below.

***Planning process***

![Planning](../images/highlightplan.png)

To plan a solution, you could use Microsoft Office Tools or other preferred program or method to chart out what you need. Each heading will guide through what you need to consider.

If you already have a process workflow mapped out, you can go straight to [designing and building](getting-started/create_process/design_process.md) in Kianda. 



## Planning your design ##

Design considers what a process needs to do and how it might look. Information can be gathered through various methods like Really Round Robin, hackathons and surveys, and captured in product vision boards. Using the 5W's of who, what, when, where and why, along with how, can help in project initiation phases to get the necessary information. 

In particular consider what **forms** do you need in your process. What kind of **fields** will be used to get the data you seek? What about information you need to provide to form users? Connecting to **datasources** like information in SharePoint, Salesforce or SAP will make your processes dynamic and always up to date.

In the example of a Training Request process, two forms are required: 1) Training Request form and 2) Training Approval form. Information sought is listed below with potential field types in brackets. Information provided by each form, for example a SharePoint list for users to scroll through, is also listed.

| 1) Training Request Form  |                                      |                                  |                            |
| ------------------------- | ------------------------------------ | -------------------------------- | -------------------------- |
| **Information provided:** | Type of Training (a SharePoint list) |                                  |                            |
| **Information needed**:   | Employee Name (textbox)              | Reason for the Request (textbox) | Line Manager (user picker) |


| 2) Training Approval Form |                                              |                          |
| ------------------------- | -------------------------------------------- | ------------------------ |
| **Information provided**: | Name, Reason, Type (group from Request form) | Line Manager (signature) |
| **Information needed**:   | Decision (a Yes/No  radio list)              | Feedback (text box)      |

It might help to know what kind of fields there are in Kianda and to keep this in mind when capturing requirements, see Kianda [Controls](/getting-started/create_process/controls.md).



## Planning interaction ##

Interaction considers how users will use the process and what series of events might happen to create different desired outputs. Decide on the sequence of events and what **rules** can be applied to create a trigger for the next event.

In the Training Request process, we'll introduce **Submit** buttons to trigger actions, and a **Rule** so that the form will appear differently based on different user inputs.

| 1) Training Request Form |                                                      |                                     |
| ------------------------ | ---------------------------------------------------- | ----------------------------------- |
| **Actions**:             | Submit (button) allows Employees to submit a form.   | Save (button) to save a draft form. |
| **Rule**:                | Send email to a Line Manager when form is submitted. |                                     |


| 2) Training Approval Form |                                                              |                                 |
| ------------------------- | ------------------------------------------------------------ | ------------------------------- |
| **Actions**:              | Submit (button) allows Line Managers to submit an approval.  | Save (button)  to save a draft. |
|                           | The approval appears in a dashboard for the Training Manager. |                                 |
| **Rule**:                 | If Yes is chosen from a radio list, then input signature.    |                                 |
|                           | If No is chosen, then hide the signature and show a Reason text box. |                                 |

It might help to know what kind of rules there are in Kianda and to keep this in mind when capturing requirements, see Kianda [Rules](/getting-started/create_process/rules.md).



## Planning management ##

Finally you need to consider **who will have access** to the information. When designing forms you can enable elements within a form so that they appear as visible-only or editable. 

You also need to consider who are the **form owners**, that is who will have editing access to the forms themselves. This information is needed when you create a process and add forms. At this point you will need to decide what users, or groups will act as form and process administrators. 

| 1) Training Request Form |                                                       |
| ------------------------ | ----------------------------------------------------- |
| **Access**:              | All Employees can access the form.                    |
| **Owner**:               | Only the Training Manager can edit the form template. |

| 2) Training Approval Form |                                                       |
| ------------------------- | ----------------------------------------------------- |
| **Access**:               | Only Line Managers can access the form.               |
| **Owner**:                | Only the Training Manager can edit the form template. |



## Summary of requirements ##

Finally we can summarise all the information we need in a spreadsheet. Field types or controls and rules will become more familiar as you work with Kianda. For now use this example as a way to get to know what is possible in Kianda.

***Examples of Requirements for a Training Request and Approval Process***

![Training Process requirements](../images/trainingreq_orig.png)


### What's next  ![Idea icon](../images/18.png) ###

Now that you know what to consider and have a design in mind, you can go to [**design your process**](getting-started/create_process/design_process.md) to learn how to get started in the Kianda **Designer**. You can use the template below, populated for a sample Training Process, to help get you started:

<a href="getting-started/create_process/files/template.xlsx" Requirements template>
Requirements template
</a>

If you would like to learn more about citizen development, have a look at Kianda's articles on the Project Management Institute (PMI) blog: https://www.projectmanagement.com/blog-post/69464/citizen-development-part-2--getting-started




### **To return to the previous pages click on the links below**  ![Idea icon](../images/10.png) 

- [**What is low-code development**](getting-started/welcome/low_code.md)
- [**What is no-code development**](getting-started/welcome/no_code.md)
- **[Logging in to Kianda](getting-started/logging_in/)**
- **[Create your first Kianda process](getting-started/create_process/)**
- [**Add forms**](getting-started/create_process/create_form.md)
- [**Add controls and rules**](getting-started/create_process/add_form_elements.md)



