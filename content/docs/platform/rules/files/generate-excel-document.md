---
title: "Generate excel workbook"
typora-root-url: ..\..\..\..\..\static
---

This rule generates an Excel workbook from data stored in the process using a template.  
![Send email rule dialog box](/images/generateexcelworkbook.png)

## When to use 
Use this rule to dynamicaly generate excel workbooks based on form or process data. This data can be available inside tables or in any field

Associate this rule to any form element.

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)

## How to use

Generate an excel workbook dynamically from process data.

Workbook generation based on XLSX template with dynamic form mappings		

**Note**: Kianda task-pane is required for mapping the field values to the excel template. Download the Kianda task pane from the Office store.

Generating MS excel document using Kianda is just a matter of few simple steps. For example, lets generate file on submission with fields like first name, last name, DOB, email, address, city and country. To do so:

Go to Microsoft Excel.
Have the template ready with the above fields.
Click on the Kianda Task-pane on the right top corner (Home page).
Now, login to Kianda using your User name and Password.
Click on two-sided arrows ⇄  and select a process from the drop-down.
Now place the cursor next to the field on the word document, select the appropriate field on the Kianda Task-pane and click on 'Insert' (repeat this for all the fields).
Save the document and go back to Kianda. Navigate to Designer > and select appropriate process.
Add two file fields on the form. First file field should store the above saved template (this template should not be deleted and this field should be connected to data source).
Select the 'Submit' button and navigate to File management > Generate excel workbook
You can optionally add conditions.
Now, Select document template as the first file field with template stored in it and Select document destination as the second file field.
Click on 'OK'



