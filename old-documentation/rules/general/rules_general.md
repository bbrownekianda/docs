# Business Process Rules

Business rules are what makes Kianda forms come alive. They represent the actual actions users intend to perform when they interact with form components.??

#### Categories

- **Workflow** - Enables you to execute actions that might change the flow of the information within a process. 
- **Communications** - Enables sending emails or meeting requests or even user (push) notifications.
- **Data** - This is an important and flexible rule group because it allows you to configure CRUD (Create, Read, Update and Delete) actions to configured data sources.
- **Users** - This enables you to retrieve a user property, updating user properties or lookup for a user based on a user attribute.
- **File management** - Allows operations such as the generation of a word document and conversion to PDF and more.
- **Tables** - Provides specialised rules to enable working with tables like sorting, copying table rows to another table and more.
- **Dates** - Enables convenient date calculation with advanced options like ignoring weekends or special dates.
- **Form actions** - Allows operations like submit, save, close and delete forms. 
- **SharePoint** - Provides a variety of operations to be performed on the SharePoint connection. These rules include operations like create a list, find a user, define permission to an item, check-in / out an item or adding a user to a SharePoint group.
- **KiandaAI** - Provides...

#### Working with rules
##### Where to Add a rule
1. To a field so that it is triggered when ??
2. To a form - will be triggered on load
3. To a process - will be triggered on load
Do all rules apply to each of these? Ask SS??

You can add this rule: Add to every rule??
- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

???explain on load


##### How to Add a rule
HELP FORM??
To add a rule to a specific component:

Select the field you want.
Under Add a rule, select the rule you want.
Edit the rule and click 'OK' - the rule will be displayed on the right-hand side of the page
VIDEO??

##### How to Copy a rule
FROM HELP??
Duplicating rules can be very useful in case you have similar rules that are in different fields. To duplicate a rule:

Select the field with the desired rule
Click on the Clone rule button, next to the rule name
Optionally, modify the rule settings
VIDEO??
Can I duplicate a rule and apply it to another form?:
FROM HELP??
Kianda forms allow you to do that! On this example, we are replicating a rule from a submit button in one form, to a submit button in another:

Select the field which contains the rule.
Click on the clone icon, next to the rules title.
Click on the Copy to another field checkbox - leaving it unchecked will clone the rule to the same field.
A list field will appear and you can select any field from any existing form in the current process.
Click 'OK'.
VIDEO

##### How to View a rule

##### How to Edit a rule

##### How to Disable a rule

##### Where to place a rule in a list of rules

Yes, and it is more straightforward than you might think:

Select the field with the rules.
On the Rules section, drag and drop the rules in the order you want them.
Submit, save, close
If there is a Condition, then the fields must be set before it is run
Example: Set Status, Send Email, Submit, Save, Close

#### Conditions

Flexible and dynamic conditions form an important component to make forms fully dynamic. It enables you  to create natural language conditions when rules should be triggered.

![Condition Editor](images\condition-editor.png)???find image

Link to edit a condition help??? blue button 'Edit conditions', then 'Add a conditions group' or 'add condition' or 'Remove group' Delete button 'And' or 'or'

FROM HELP??
To configure a rule to conditionally execute an action:

Click on Edit conditions button within the rule.
Add the conditions that satisfy your scenario.
Multiple conditions can be grouped with condition groups.
VIDEO??

#### Custom rules

Under custom rules, you will find any custom-developed rules available under your developer section. Custom rules provide access to rules that are built for extensibility of Kianda capabilities. This is particularly used in situations when existing rules do not provide the required functionality.

Custom rules have the purpose of providing a user interface for the end-users. If you need to build "a rule" then you should use a custom rule widget.

It allows a developer to quickly build a reusable component that would then be used by process designers in real processes.

Check-out the [development](development.md) section for more details on how to build custom widgets in Kianda.

[Workflow](rules_workflow.md)

[Communications](rules_communications.md)

[Data](rules_data.md)


[Users](rules_users.md)

[File management](rules_file_management.md)

[Tables](rules_tables.md)

[Dates](rules_dates.md)

[Form actions](rules_form_actions.md)

[Sharepoint](rules_sharepoint.md)

[Kianda_AI](rules_kianda_ai.md)
	

