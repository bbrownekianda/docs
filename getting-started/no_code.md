# What is No-Code Development?

No-Code development involves the creation of applications or business process without the need to code. This means any no-code platform must provide a Graphical User Interface (GUI) to easily allow **citizen developers** or non-IT business professionals the ability to create and deploy digital solutions to meet business needs. Regardless of how the solution is created the output must meet all the requirements of a modern web application, being accessible through all major browsers and platforms, responsive in design so that it can be used on a variety of devices.

Kianda form **Designer** provides an intuitive interface where both technical and non-technical users can quickly start building forms for any use case for use on any type of device. You don't need to know how to code to take advantage of Kianda's key features to create modern web application design. These features include:

1. **[Multibrowser and multidevice access](#multibrowser-and-multidevice-access)** to a platform which can be used online and offline.
2. **[Intuitive Designer](#intuitive-designer)** to create forms at a click, with options to **clone** and **activate several forms** together.
3. Wide array of [**predefined fields**](#predefined-fields) to choose from.
4. [**Responsive** **form layout**](#responsive-form-layout).
5. Vast selection of [**properties and settings**](#properties-and-settings) to customise your design.
6. [**Connection to external datasources**](#connection-to-datasources) to create highly dynamic forms, for example lists with cascading dropdown options.
7. Ability to allow **multimedia capture** and image annotation through forms
8. [**Rules**]() to make forms reactive and interactive
9. **Anonymous forms** that can be shared externally
10. [**Dashboards**](#dashboards) to monitor processes in detail.
11. Options to **create custom** fields, rules and dashboard widgets

Click on the links above to find out more. 



## Multibrowser and multidevice access

Kianda is a **Progressive Web Application** **(PWA**) Kianda which means it can be used across a range of up-to-date browsers, on any platform - Windows, MacOS or Linux - and on any device. As a PWA, this means you can browse Kianda when not online, increasing engagement and availability. This is particularly useful when operating in remote areas, for example performing a maintenance check of a wind turbine or other equipment in the field, and capturing information in draft form for submission later on back at the office. 

***Example of using Kianda offline on a smartphone***

<video width="20%" style="width:20%" controls>
    <source src="../videos/offline.mp4">
    Your browser does not support the video tag.
    </source>
</video>


## Intuitive Designer

Kianda form **Designer** provides an easy way to build forms and process components. 

The key components of the form designer are:

1. **Left-hand pane** is used to add form elements like **controls** and **rules**. This pane also houses the **Exit** Designer ![Exit](images/exitdesign.png) **Save** ![Save](images/save.png)  **Preview** ![Preview](images/preview.png) and **Publish** ![Publish](images/publish.png) buttons.
2. Central **form canvas** displays the current form you are working on and changes in real time.
3. **Right-hand pane** is used to view and edit process, form and field **properties** and **rules**.

***Kianda Designer***

![Form designer](images/formdesigner_frame.png)

For more information on how to use [Designer](getting-started/designer.md), click on the link and view the video below. 

***How Kianda Designer works***

<video width="100%" style="width:100%" controls>
    <source src="../videos/designerintro.mp4">
    Your browser does not support the video tag.
    </source>
</video>


## Predefined fields ##

Kianda comes with 16 predefined field widgets, see [Controls](getting-started/controls.md) for a full list. You can also use [Kianda Designer](low-code.md) to create custom fields in case none of these satisfy your specific needs and if you have some level of development skills.

The default fields fall into four main categories of fields:

1. **Input** - Input fields include the most common data fields such as textbox, user picker, date field, table, checkbox, drop-down and number fields.
2. **Layout** - Layout fields are the fields that serve the purpose of perfecting the layout of your form. They include responsive panels, dialog box, field groups and rich text fields.
3. **Action** - Action fields are fields that allow user interface actions like buttons, links or even signature components.
4. **Custom**  - Under custom fields, you will find any custom-developed fields developed using Kianda [Developer](getting-started/low_code.md).

For example layout fields play an important role when building a modern user interface, allowing you to add **Richtext** and **Dialog boxes**. Together these fields can be used to create a modal dialog, allowing you a form designer to create an alert for a form user, for example when requiring user confirmation or making a final decision or check. 

***Creating a modal dialog***

<video width="100%" style="width:100%" controls>
    <source src="../videos/modaldialog.mp4">
    Your browser does not support the video tag.
    </source>
</video>


In the example above, we use a modal dialog to display a simple **alert** to the user. To create this the steps are:

1. Click on **Controls** > **Layout** > **Dialog**. 
1. Give the Dialog a **title**. 
2. Click on the dialog component to insert other fields within it.
3. You can add any field to your dialog, in this case, for example click on **Rich text** and edit your information.
4. To preview how your dialog box will be displayed, you can use the **Preview** button, on the dialog 



## Responsive form layout

Form fields are made to with a mobile-first approach giving you design once and deploy everywhere opportunity.

By using the **Layout** option under the property panel you will be able to simply define the layout of your fields or panels within a form. Clicking on the **Collapse or Expand** button ![Collapse or expand button](images/collapse.png)quickly uncovers the layout mode for desktop and mobile.

![Layout mode](images/layout.png)

This allows you to specify a layout made of 1 to 12 columns and is based on bootstrap, a popular CSS  framework that allows designing web interfaces with a mobile-first approach.

***Editing forms***

<video width="100%" style="width:100%" controls>
  <source src="../videos/editfields.mp4">
    Your browser does not support the video tag.
    </source>
</video>


## Properties and settings

Kianda form usability is brought to life with the help of the various input fields available that are specifically adapted to work in mobile, tablet or desktop modes.

From the textbox, date picker, numeric input, file upload and table, Kianda offers a flexible array of controls that can be **adjusted** through properties and settings to work with a myriad of scenarios.

Each field comes with its own set of settings like autofill for textbox and currency format for numeric input. 

The following are some of the common properties of input fields:

- Title - Every field comes with a title property that is usually displayed on top of the field and can serve as a prompt to a user.
- Required - Using this checkbox makes a field mandatory for form users to fill in.
- Visible - Displays the field in the form if checked.
- Layout - Defines both desktop or mobile layout.

In addition to the above, each field has it's own set of settings, for example a **list** can have data entered manually, via a form, or from a data source such as SharePoint or Salesforce and that list can be displayed as a dropdown, radio, multiselect or checkbox list. 



## Connecting to datasources ##

By connecting Kianda forms to existing datasources like lists in SharePoint, Google Drive or SQL tables to name a few examples, your processes will always stay relevant, up-to-date and perform as your data grows, creating a scalable solution. 

There are currently 19 different predefined data connectors that allow you to connect to Kianda processes, see [Data connectors](getting-started/dataconnect.md/#data-connector-list) for a full list. 



### Forms

Forms are an important component of any process, they might be used as stages of a process and could be made active individually or at the same time (parallel forms).

The key rules for working with forms are:

1. Forms are assignable - means that only a form assignee can edit a particular form. This can be a combination of users and groups.
2. Only form owners can edit a given form by default. Any other user with access to view the form will see it in read-only mode.
3. Multi-step processes use the concept of "current form". Only the form matching the process status will be made editable.
4. In a multi-step process, other forms that are not "current form" can be configured to **activate with** the current form. Meaning they might also be editable and will form a form group.

The rules above work together to determine if the form is in edit mode or display mode. Form designers have at their disposal [business rules](business-rules.md) such as *assign form*, *go to form* and *submit rule* to dynamically control the ability for end-users to edit a particular form or a section of a form.

***How to add new form***

<video width="100%" style="width:100%" controls>
    <source src="../videos/How to add new form 2.mp4">
    Your browser does not support the video tag.
    </source>
</video>


1. Click on *Add form*, on the top right side of the page.
2. Give your form a title.
3. The *name* is a unique identifier - you can leave it as it is.
4. You can define an owner to the form.
5. Activate with will decide when the form will be active - if you leave it blank, the new form will be activated *sequentially* after the first form is submitted.
6. Select *Submit mode* - you can submit just the current form or all forms that are in edit mode.
7. Check *Enable quick actions* if you want the form to be edited or re-assigned.
8. Provide a user or group in the *Quick action user (s)* to whom you would like to permit to re-assign or edit the form.

## Anonymous Forms

Anonymous forms are a great way of allowing people outside of your organisation to interact with your processes. 

It could be something as simple as a contact form or a feedback form but as we all know a contact form never ends with the contact submission. There is always a process or a series of steps behind each public/anonymous form that might culminate with an actionable result back to the person that started the submission.

We have seen a few examples of how people use anonymous forms in Kianda. From simple feedback forms to GDPR data requests that hope between multi divisions before sending back a response to the requester with the level of information held by the organization.

Anonymous forms can be embedded in iframes and safely displayed within other web-based applications.

In Kianda there are effectively 2 types of anonymous forms

- New process anonymous form
- Existing process anonymous form

### New instance anonymous form URL

To set up a globally available link for allowing external users to create a new instance, perform the following steps within the form designer:

1. On the top right corner of the designer click on the settings button.
2. Then click the option "Enable anonymous sharing of forms" to Yes.
3. Click the button "New Link" to generate a new anonymous link.

![Anonymous Form Setting](../images/anonymous-forms.png)

### Existing instance anonymous form URL

To setup existing instance anonymous form one needs to use the anonymous form rule to generate a new anonymous link at the runtime that will point to an existing process record that can then be shared with external users.

Note that for this to work steps 1 and 2 of New Instance Anonymous form is still required.

The following are some of the key options of the anonymous link rule:

- Form to share (any form within an existing process).
- Link expires settings: Number of uses, time-based or never expire.
- Message to display on submission.

**Important**: There can be only one active link of each type for a given process. Once a new anonymous link is created for a process it will automatically expire the previous of the same type if a link existed.

## Input fields

Kianda forms usability is brought to life with the help of the various input fields available that are specifically adapted to work in mobile, tablet or desktop modes.

From the textbox, date picker, numeric input, file upload and table, Kianda offers a flexible array of controls that can be adjusted to work with a myriad of scenarios.

Key properties of fields:

Each field comes with its own set of settings like autofill for textbox and currency format for numeric input. 

The following are some of the common settings of input fields:

- Title - Every field comes with a title property that is usually displayed on top of the field and can serve as a prompt to a user.
- Required - This Boolean property allows making a field mandatory or not.
- Visible - Displays the field in the form or not.
- Layout - Defines both desktop or mobile layout.

### Cascading dropdown

The List field provides the opportunity to define an unlimited level cascading dropdown hierarchy very easily.

To achieve that you might connect your list to a data source table or SharePoint list then use the list data source conditions options to filter its content based on a parent list. 

![Cascading dropdown](../images/cascading-dropdown.png)

***How to create cascading dropdowns***

<video width="100%" style="width:100%" controls>
    <source src="../videos/How to create cascading dropdowns.mp4">
    Your browser does not support the video tag.
    </source>
</video>


## Input validation

Validating input in forms is quick and easy. Simply enable the **required** flag of an input field and it will automatically prevent users from submitting it empty.

The required flag will conveniently be ignored in case the field is not visible, this will allow you to configure conditionally mandatory fields.

Another way of validating input is to use the **validate input rule** this allows greater flexibility in terms of when or what to validate.

## Cloning

In the form designer, almost any of the components can be cloned. This will increase your productivity considerably and will make creating multi-step processes a breeze.

To clone either a field a panel or even a form simple select the component then click the clone button in the  properties panel in the right-hand side of the panel.

If cloning a field the cloning dialog will prompt for the destination of the new cloned field, once your choice is made, simply click ok.

***Cloning a form***

<video width="100%" style="width:100%" controls>
    <source src="../videos/Cloning a form updated.mp4">
    Your browser does not support the video tag.
    </source>
</video>


## Custom fields

Custom fields section provides access to fields that are built for extensibility of Kianda capabilities. It is particularly useful in those situations where existing fields or rules will not provide the required functionality.

Custom fields have the purpose of providing a user interface for end-users. If you need to build "an action" then you should use a custom rule widget.

It allows a developer to build a reusable component that would then be used by process designers in real processes.

Check-out the [development](development.md) section for more details on how to build custom widgets in Kianda.

## Dashboards ##

Use Kianda's predefined widgets to create charts in a dashboard page for your process. There are 7 different widgets that allow you to create a visualisation, where you can zone in on key data that you want to highlight.

![Dashboard example](images/dashboardexample2.png)

***Creating a dashboard***

<video width="100%" style="width:100%" controls>
    <source src="../videos/dashboards.mp4">
    Your browser does not support the video tag.
    </source>
</video>






## Advanced techniques

Like the cascading dropdown discussed above, several other advanced scenarios can be easily configured in Kianda. Here is a short-list:

- **Repeating section** - A repeating section can be created by adding a **panel** to a table field. This table can be configured to include a single column made of the panel that itself will include the repeating fields of your repeating section.
- **The capture of media** - Kianda enables mobile users to directly capture pictures, video or audio just like a native application.
-  **Background save** - By making use of PWA principles (Progressive Web Application) Kianda allows the ability to perform background operations. This is useful when, for example, a mobile user picks-up their phone to perform a quick action and places it back in his pocket. Operations will continue in the background allowing all data to be captured.
- **Image annotation** - Kianda allows for image annotation online or offline.
- **Multi-column / row layout** - Making multi-column responsive interfaces is quite easy. Simply add two panels into a form that only use half of the screen (6 columns) then add fields inside panels and you have multiple column layouts. Adding a panel using 12 columns gives you a row.
- **Form tab colour and icon** - Form tabs can be quickly customised to display their icons or tab colours, it is also possible to define custom colours for selected and completed form tabs.
- **Hide form tab and left nav** - This is self-explanatory, yes you can hide the default navigation elements.