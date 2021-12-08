# SharePoint

[toc]

##### Create a list 	 
Creates a new list on SharePoint	
SharePoint specific rule. Allows the creation of a new list in a SharePoint site		

##### Create a site 
Creates a new site on SharePoint	
Used to create a new web in SharePoint. Enables the use of a site template		

##### Create a group
Creates a new group on SharePoint	
Enables the creation of SharePoint group		

##### Find a user
Finds a user on SharePoint	Finds or searches for a user within SharePoint		

##### Add a user to a group
This rule adds a SharePoint user to a SharePoint group

It is important to note the difference between Sharepoint users and Kianda users.  Sharepoint users are users of the Sharepoint system.  Kianda users are users of the Kianda system.

If there is a user group assigned to a SharePoint url then you can select a Kianda user to be added to that group.

To add a new SharePoint user
1. Select the Submit button, for example.
2. Click on Add a rule->SharePoint ->Add a user to a group
3. Select a SharePoint data source from the drop-down list.  Two new fields will appear: 
	For Group title field, select the field where the group title is stored e.g. a list field.
	For Username or User Id, select the field where the Username or User id is stored.
7. The final two sections are optional:
	Under On success mapping, click on Add mapping. 
		For Form Field, select a field to store the text. 
		For Data source field or text, either enter the text or 
			select a field where the text is stored.
	Under On error mapping, click on Add mapping. 
		For Form Field, select a field to store the text. 
		For Error message or text, either enter the text or 
			select a field where the text is stored.
10. Move the rule...

##### Remove a user from a group
This rule removes a SharePoint user from a SharePoint group

It is important to note the difference between Sharepoint users and Kianda users.  Sharepoint users are users of the Sharepoint system.  Kianda users are users of the Kianda system.

To remove a user from a group
1. Select the Submit button, for example.
2. Click on Add a rule->SharePoint ->Remove a user from a group
3. Select a SharePoint data source from the drop-down list.  Two new fields will appear: 
	For Group title field, select the field where the group title is stored e.g. a list field.
	For Username or User Id, select the field where the Username or User id is stored.
7. The final two sections are optional:
	Under On success mapping, click on Add mapping. 
		For Form Field, select a field to store the text. 
		For Data source field or text, either enter the text or 
			select a field where the text is stored.
	Under On error mapping, click on Add mapping. 
		For Form Field, select a field to store the text. 
		For Error message or text, either enter the text or 
			select a field where the text is stored.
10. Move the rule...


##### Reset an item permissions NOW
This rule changes the SharePoint permissions for a given list, document or folder.

To reset the permissions of an item 
1. Select the Submit button, for example.
2. Click on Add a rule->SharePoint ->Reset an item permissions
3. Select a SharePoint data source from the drop-down list.  Three new fields will appear:

 	For Item Type, choose from the options: Site, List or other Item
 	For Site relative URL field, copy in the URL of the Sharepoint item. [You can also store 			the URL in a field and select the field from the drop-down list.]
 	For Existing permissions, choose either Add to existing or Replace existing
6. Under Input mapping section, click on Add mapping.
	For User or Group id, select the field where the user is stored.  This could be either a       			User Picker field or a text field.
	Select the Permission level from the drop-down list.  Examples are Edit or View only.
7. The final two sections are optional:
	Under On success mapping, click on Add mapping. 
		For Form Field, select a field to store the text. 
		For Data source field or text, either enter the text or 
			select a field where the text is stored.
	Under On error mapping, click on Add mapping. 
		For Form Field, select a field to store the text. 
		For Error message or text, either enter the text or 
			select a field where the text is stored.
10. Move the rule...

##### Check in / out an item 
Checks in or out a SharePoint item	
Checks in or out a file in SharePoint		

##### Get attachments 
Loads item(s) attachments into a file input	
Reads the attachments from a SharePoint list 		

##### Create anonymous link  
Create SharePoint anonymous link(s) from a SharePoint file input	
Creates anonymous links for a SharePoint held file	