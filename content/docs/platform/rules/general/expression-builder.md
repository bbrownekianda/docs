---
title: "Expression builder"
weight: 3
typora-root-url: ..\..\..\..\..\static
---

Expressions allow you to put together form **identifiers** (form field IDs) and **constants** with **operators** and **functions** to return a **dynamic value** that can be used in various places – for example, in a form or field rule to automate processes.

***Expressions***

![Expression elements](https://academy.kianda.com/wp-content/uploads/2022/02/expressions.gif)

For example, expressions could be used in the body of an automated email sent using the **Send email** rule, as shown here:

***Expression example***

![img](https://academy.kianda.com/wp-content/uploads/2022/03/expressioneg-1.gif)

In the example above, **[RequesterName]** and **[category]** are identifiers, that is unique IDs for form fields. **ProcessLink()** is a function that will return a link to that process instance. Using the expressions above in an email will mean that every time an instance of the process runs, the values will be presented in an automated email, creating greater efficiencies and personalising the email for the recipient.

### Expression builder

The expression builder is used to build expressions. You can search for fields and click on **Add to expression**.

![Expression builder dialog box](/images/expressionbuilder.png)

In addition to defining your own expressions there is a set list of expressions found under **References**, see table below for meaning.

| Expression                                    | Function                                                     |
| :-------------------------------------------- | :----------------------------------------------------------- |
| +, -, /, \*                                   | Performs one of the basic mathematical operations: add, subtract, divide or multiply. |
| Sum(arg1, arg2, ...)                          | Returns the sum of the arguments listed between the parentheses. |
| Date(arg1)                                    | Converts the argument into a date.                           |
| DateAdd(dateArg, day, month, year, hour, min) | Adds time to a given date. The date is stored in dateArg and the time to be added is stored in the day, month, year, hour and min arguments. |
| Status()                                      | Returns the status of the current process.                   |
| ProcessID()                                   | Returns the ID of the current process.                       |
| FormOwner(formName)                           | Returns the form owner(s) for the given form.                |
| FormCompleted(formName)                       | Returns the date completed for the given form.               |
| Pad(value, size, symbol)                      | Adds left padding to the value with the symbol provided.     |
| QueryString(parameter)                        | Returns the URL query string for the given parameter (or an empty string if undefined). |
| IsOnline()                                    | Returns "yes" or "no" depending on the status of the online connection. |
| ProcessLink()                                 | Returns the HTML link to the current process  The link text can be added between the parantheses e.g. ProcessLink("click here"). This expression is for use in emails and rich text fields. |
| Digest()                                      | Returns a summary of changes to fields in the current process.  A table will be given with the original and new values. |
| Digest('fieldName1','fieldName2')             | Returns a summary of the changes for the given fields.  See note below. |
| GetFieldText('fieldName')                     | Returns the text in the given field. See note below.         |
| GetFieldValue('fieldName')                    | Returns the value in the given field. See note below.        |

**Note**: In the case of the last three expressions, you should select a field which contains data.  If you give the name of a button field for example, then no data will be returned.

