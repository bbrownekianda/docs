---
title: "Generate word document"
typora-root-url: ..\..\..\..\..\static
---

This rule generates a word document from data stored in the process using a word DOCX template.  
![Send email rule dialog box](/images/generateworddocument.png)

## When to use 
Use this rule when your process requires dynamic document generation with high fidelity. This rule will use a word template previously mapped with smart tags using the Kianda task pane to generate a document containing the form captured from the process or data source.

Associate this rule to any form component. 

## How to use
Note: Kianda task-pane is required for mapping the field values to the word document.

Generating word document using Kianda is just a matter of few simple steps. For example, lets generate a word document on submission with fields like first name, last name, DOB, email, address, city and country. To do so:

Go to Microsoft Word.
Have the template ready with the above fields (as shown in the video).
Click on the Kianda Task-pane on the right top corner (Home page).
Now, login to Kianda using your User name and Password.
Click on two-sided arrows ⇄  and select a process from the drop-down.
Now place the cursor next to the field on the word document, select the appropriate field on the Kianda Task-pane and click on 'Insert' (repeat this for all the fields).
Save the document and go back to Kianda. Navigate to Designer > and select appropriate process.
Add two file fields on the form. First file field should store the above saved template (this template should not be deleted and this field should be connected to data source).
Select the 'Submit' button and navigate to File management > Generate word document.
You can optionally add conditions.
Now, Select document template as the first file field with template stored in it and Select document destination as the second file field.
You can chose to convert to PDF and click on 'OK'

