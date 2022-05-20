---
title: "Success/Error Mapping"
typora-root-url: ..\..\..\..\..\static
weight: 3
---

Success/Error mapping can be used to populate fields within the Kianda form depending on the success or failure of a rule being executed.

 

**When to use:** 

Success/Error mapping should be used when after the execution of a rule you wish to have fields populated with specific values. 

 

**You can add this rule:**

·    to a field

·    to a form

·    to a process (the rule will run on load)

 

**How to use:**

1. For on success mapping select the “form field” and chose the field within the form which you want to store the information. 

2. Then in the “data source field or text” you can select the column/field within your respective data source and this value will be stored in the “form field”.

3. For on error mapping, you simply need to select the field within the form which will store the error message

4. Then select the error message from the dropdown. This error message will be a system generated error which will indicate what if anything has gone wrong when the rule executed.

5. Click OK and the mapping is set.
