---
title: "What is No-Code Development?"
linkTitle: "What is no-code?"
weight: 2
typora-root-url: ..\..\..\..\static
---

No-Code development involves the creation of applications or business process without the need to code. A no-code platform provides a Graphical User Interface (GUI) to easily provide **citizen developers** or non-IT business professionals the ability to create and deploy digital solutions to meet business needs. Regardless of how the solution is created the output must meet all the requirements of a modern web application, being accessible through all major browsers and platforms, responsive in design so that it can be used on a variety of devices.

Kianda form **Designer** provides an intuitive interface where both technical and non-technical users can quickly start building forms for any use case for use on any type of device.

You don't need to know how to code to take advantage of Kianda's key features to create modern web application design. These features include:

1. **[Multibrowser and multidevice access](#multibrowser-and-multidevice-access)** to a platform which can be used online and offline.
2. **[Intuitive Designer](#intuitive-designer)** to create forms at a click, with options to **clone** and **activate several forms** together.
3. Wide array of [**predefined fields**](#predefined-fields) to choose from.
4. [**Responsive** **form layout**](#responsive-form-layout).
5. Vast selection of [**properties and settings**](#properties-and-settings) to customise your design.
6. [**Connection to external datasources**](#connecting-to-datasources) to create highly dynamic forms, for example lists with cascading dropdown options.
7. Ability to allow **[multimedia capture](#multimedia-capture)** and image annotation through forms.
8. [**Rules**](#rules) to make forms reactive and interactive.
9. [**Anonymous forms**](#anonymous-forms) that can be shared externally.
10. [**Dashboards**](#dashboards) to monitor processes in detail.
11. Options to [**create custom**](#creating-custom-fields) fields, rules and dashboard widgets

Click on the links above to find out more. 



## Multibrowser and multidevice access

Kianda is a **Progressive Web Application** **(PWA**) Kianda which means it can be used across a range of up-to-date browsers, on any platform - Windows, MacOS or Linux - and on any device. As a PWA, this means you can browse Kianda when not online, increasing engagement and availability. 

This is particularly useful when operating in remote areas, for example performing a maintenance check of a wind turbine or other equipment in the field, and capturing information in draft form for submission later on back at the office. 



## Intuitive Designer

Kianda form **Designer** provides an easy way to build forms and process components. 

The key components of the form designer are:

1. **Left-hand pane** is used to add form elements like **controls** and **rules**. This pane also houses the **Exit** Designer ![Exit](/images/exitdesign.png) **Save** ![Save](/images/save.png)  **Preview** ![Preview](/images/preview.png) and **Publish** ![Publish](/images/publish.png) buttons.
2. Central **form canvas** displays the current form you are working on and changes in real time.
3. **Right-hand pane** is used to view and edit process, form and field **properties** and **rules**.

***Kianda Designer***

![Form designer](/images/formdesigner_frame.png)

For more information on how to use [Designer](/docs/getting-started/create-first-process/add-forms/designer), click on the link and view the video below. 

***How Kianda Designer works***

<video width="100%" style="width:100%" controls>
    <source src="/videos/designerintro.mp4">
    Your browser does not support the video tag.
    </source>
</video>



## Predefined fields ##

Kianda comes with 16 predefined field widgets, see [Controls](/docs/getting-started/create-first-process/design-and-build/add-controls-and-rules/) for a full list. You can also use [Kianda Developer](/docs/getting-started/welcome/low-code/) to create custom fields in case none of these satisfy your specific needs and if you have some level of development skills.

The default fields fall into four main categories of fields:

1. **Input** - Input fields include the most common data fields such as textbox, user picker, date field, table, checkbox, drop-down and number fields.
2. **Layout** - Layout fields are the fields that serve the purpose of perfecting the layout of your form. They include responsive panels, dialog box, field groups and rich text fields.
3. **Action** - Action fields are fields that allow user interface actions like buttons, links or even signature components.
4. **Custom**  - Under custom fields, you will find any custom-developed fields developed using Kianda [Developer](low_code.md).

For example, layout fields play an important role when building a modern user interface, allowing you to add **Richtext** and **Dialog boxes**. You can use these fields together to create a modal dialog, allowing you a form designer to create an alert for a form user, for example when requiring user confirmation or making a final decision or check. 

***Example of fields in action - creating a modal dialog***

<video width="100%" style="width:100%" controls>
    <source src="/videos/modaldialog.mp4">
    Your browser does not support the video tag.
    </source>
</video>



## Responsive form layout

Form fields are made to with a mobile-first approach giving you design once and deploy everywhere opportunity.

By using the **Layout** option under the property panel you will be able to simply define the layout of your fields or panels within a form. Clicking on the **Collapse or Expand** button ![Collapse or expand button](/images/collapse.png)quickly uncovers the layout mode for desktop and mobile.

![Layout mode](/images/layout.png)

This allows you to specify a layout made of 1 to 12 columns and is based on bootstrap, a popular CSS  framework that allows designing web interfaces with a mobile-first approach. You can see this layout in action in the video below.

***Editing forms***

<video width="100%" style="width:100%" controls>
  <source src="/videos/editfields_inuse.mp4">
    Your browser does not support the video tag.
    </source>
</video>



## Properties and settings

Kianda form usability is brought to life with the help of the various input fields that are specifically adapted to work in mobile, tablet or desktop modes.

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

There are currently 19 different predefined data connectors that allow you to connect to Kianda processes, see the video below for the full list.

***Example connecting to a SharePoint datasource***

<video width="100%" style="width:100%" controls>
  <source src="/videos/dataconnectsharepoint.mp4">
    Your browser does not support the video tag.
    </source>
</video>

The example above shows how a list field can be used in a form connected to SharePoint information, so as that list grows on SharePoint, then the process will information more information dynamically.

The list field in conjunction with datasources, provides the opportunity to define an unlimited level cascading dropdown hierarchy very easily. 

### Cascading dropdown example

For example if you have SharePoint or Salesforce lists of customers in different countries and different cities, then you can use the list data source conditions options to filter content based on a parent list.

The video below shows how cascading lists connected to data sources works in practice.

***How to create cascading dropdowns***

<video width="100%" style="width:100%" controls>
    <source src="/videos/cascadinglists.mp4">
    Your browser does not support the video tag.
    </source>
</video>



## Multimedia capture
When creating forms, there are options to capture capture user input in a variety of ways, by clicking on radio buttons, selecting options from dropdown lists, entering text, uploading files, capturing images, videos, QR codes and voice input to name a few. See the video below to see examples of possiblities with forms.

***Examples of possibilities with Kianda forms***

<video width="100%" style="width:100%" controls>
  <source src="/videos/possibilities.mp4">
    Your browser does not support the video tag.
    </source>
</video>



## Rules

Rules are an important component of any process as they can be used to trigger automated actions, requiring minimal user management once created. There are 60 predefined rules in Kianda, covering workflow applications, communications and file management to name a few.

The video below shows an example of a rule that send an automated email, once a Submit button is pressed on a form.

***Examples of possibilities with Kianda forms***

<video width="100%" style="width:100%" controls>
  <source src="/videos/rules.mp4">
    Your browser does not support the video tag.
    </source>
</video>




## Anonymous Forms

Anonymous forms are a great way of allowing people outside of your organisation to interact with your processes, for example simple feedback forms to GDPR data requests that hop between multi divisions before sending back a response to the requester with the level of information held by the organization.

It could be something as simple as a contact form or a feedback form but as we all know a contact form never ends with the contact submission. There is always a process or a series of steps behind each public/anonymous form that might culminate with an actionable result back to the person that started the submission.

Anonymous forms can be embedded in iframes and safely displayed within other web-based applications.


## Dashboards ##

Use Kianda's predefined widgets to create charts in a dashboard page for your process. There are 7 different widgets that allow you to create a visualisation, where you can zone in on key data that you want to highlight.

***Creating a dashboard***

<video width="100%" style="width:100%" controls>
    <source src="/videos/dashboards.mp4">
    Your browser does not support the video tag.
    </source>
</video>



## Creating custom fields

The Custom fields section of Kianda, called **Developer** provides access to fields that are built for extensibility of Kianda capabilities. It is particularly useful in those situations where existing fields or rules will not provide the required functionality.

Custom fields have the purpose of providing a user interface for end-users. If you need to build "an action" then you should use a custom rule widget.

It allows a developer to build a reusable component that would then be used by process designers in real processes.

Check-out the [development](getting-started/welcome/low_code.md) section for more details on how to build custom widgets in Kianda.



### What's next  ![Idea icon](/images/18.png) ###

If you are ready to start your no-code development journey, then follow the steps below:

![1](/images/one.png)  [**Plan your process**](getting-started/create-first-process/plan_process.md) 

![2](/images/two.png)  [**Design and build your process**](/docs/getting-started/create-first-process/design-and-build/)

![3](/images/three.png)  [**Publish your process**](/docs/getting-started/create-first-process/publish-your-process/)



### **To return to the previous pages click on the links below**  ![Idea icon](/images/10.png) 

- **[Getting started guide](getting-started/)**
- **[Welcome to Kianda](getting-started/welcome/)**
- [**What is low-code development**](getting-started/welcome/low_code.md)
- [**Logging in to Kianda**](getting-started/logging_in/)
- [**Create your first Kianda process**](getting-started/create-first-process/)

