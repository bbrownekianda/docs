---
title: "Business rules"
weight: 2
linkTitle: "Rules"
typora-root-url: ..\..\..\..\..\static
---

Business rules are what make Kianda forms come alive. They represent the actual actions users intend to perform when they interact with form components - for example, sending automated emails, revealing certain parts of a form based on user interactions and automatically generating Word and PDF documents from completed forms. 

There are 60 predefined rules across 10 categories and they can be applied to fields (controls), forms, groups of forms or even to a whole process - see [Rules list](#rules-list) for more details.

There are two key principles to consider when working with rules:

1. [Rule design](#rule-design) - Consider the type of rule you are going to apply and what you are going to apply it to - for example, to a button, field or form. As part of your design considerations it is important to know what you can do with rules, in particular, the use of [conditions](/docs/getting-started/create-first-process/plan-your-process/conditions/) and [expressions](/docs/getting-started/create-first-process/plan-your-process/expressions/). 

2. [Rule order](#rule-order) - If there are several rules attached to an item like a button, then the order the rules are going to be executed in becomes important. You can change the rule execution order to suit your needs.

   

## How to get started ##

If you go to **Side menu** > **Administration** > **Designer**, click on a process or create a new process, and then select a form within the process so that the **Edit form** button (**Pen** icon ![Pen button](/images/penicon.png)) appears. The predefined rules will can then be found in the left-hand pane under **Add a rule**.

***Rule categories***

![Rules list](/images/ruleslist80.png)

There are 10 categories of rules available (see [Rules list](#rules-list) for the full list of names of the 60 predefined rules):

1. **Workflow** - There are seven workflow rules that represent the actions a user intends to perform when they interact with form components. 
2. **Communications** - There are four communication rules associated with user communication - for example, sending an email or triggering a user alert. 
3. **Data** - There are five data rules associated with database operations like create, update and delete. 
4. **Users** - There are four user rules associated with user properties, allowing user lookup or to update a user. 
5. **File management** - There are seven file management rules concerned with generating documents such as Word, Excel or converting to PDF. 
6. **Tables** - There are 12 table rules associated with table operations such as updating, adding and removing table rows. 
7. **Dates** - There are four date rules to calculate time and format dates.
8. **Form actions** - There are six form rules linked to actions that are part of forms - for example, submit, close or save.
9. **SharePoint** - There are 10 SharePoint associated rules such as adding, finding or removing users. 
10. **KiandaAI** - there is one KiandaAI rule related to text analysis.

An additional **Custom** category exists if Kianda **Developer** has been used to create custom rule widgets - see [Developer](/docs/getting-started/welcome/low-code/) for more details.



## When to use rules

You can add rules:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)



### Rule design ###

1. Click on an existing process by going to **Administration** > **Designer** and decide which form or field you want to apply the rule to by clicking on that item so that you're viewing it in **edit mode** (so the **Pen** icon ![Pen button](/images/penicon.png) appears) - for example, you could select a form called Training Approval or could select a button like Submit to apply a rule or rules to.

   ***Field editing***

   ![Edit mode for forms and fields](/images/submitedit.png)

2. Click on **Add a rule** in the left-hand pane and select the category of rule you want, such as **Communications**, and then click the particular rule you want to insert within that category, for example **User alert**.

 



### Rule order ###

If there is more than one rule for an item like a field or button, then you need to consider the order of execution. 

For example, for a Submit button on a form you may want a **Send email rule** to be executed first before any other rule is executed. To do this, click on the **Submit** button to make sure you are in **Edit** mode, and under **Rules** in the right-hand pane, drag the **Send email** rule to the top of the list of rules by clicking on the rule and dragging it to the top.

***Rule order***

![Rule order](/images/ruleorder.png)



## Rules list ##

This table contains a full list of the available predefined rules.

***Rules by category and title***

![Rules list](/images/rulestablecal12.gif)



### What's next  ![Idea icon](/images/18.png) ###

To learn more about control fields, go to [**Controls**](../controls/). 

To find out how to get the most out of rules, see [**Conditions**](../conditions/) and [**Expressions**](../expressions/).



### **To return to the previous pages click on the links below**  ![Idea icon](/images/10.png) 

- [**How Kianda works**](/docs/getting-started/welcome/how-kianda-works/)
- [**Plan your process**](/docs/getting-started/create-first-process/plan-your-process/) 
- [**Design and build your process**](/docs/getting-started/create-first-process/design-and-build/) 
- [**Add forms**](/docs/getting-started/create-first-process/design-and-build/add-forms/)
- [**Designer**](/docs/getting-started/create-first-process/design-and-build/add-forms/designer/)
- [**Properties**](/docs/getting-started/create-first-process/design-and-build/add-controls-and-rules/properties/)
- **[Add controls and rules](/docs/getting-started/create-first-process/design-and-build/add-controls-and-rules/)**

  

  