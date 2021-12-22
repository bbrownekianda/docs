# Send email #

This rule sends an email according to a predefined template.  Each element of the email is configurable.  The body of the email can include text and images.  Data stored in fields in the current form can be copied in dynamically.  It is also possible to add attachments to the email.



## When to use the Send email rule

You can add this rule:

- [x] to a field
- [x] to a form 
- [x] to a process (the rule will run on load)



## Before you get started ##

In advance of using this rule, you need to have created one or more forms, complete with control fields. For example an employee's 'Name' may be part of a form 'Annual Leave Request'. Then this 'Name' (text box) field can be used as an **expression** in the email to send personalised emails. 

Before you set up a 'Send email' rule you need to decide who will the email be from, for example a no-reply type email, who the email will be to, TO COME BACK TO





## **How to get started**

1. Click on an existing process by going to **Administration** > **Designer** and then click on **Rules** > Communications > Send email. 

2. Choose from the edit options:

   1. **Title** - of the email for example 'Send email to Training Managers'

   2. **Edit conditions** - click on the **Edit conditions** button ![Edit conditions button](images/editconditions.png) create conditions to send the email, for example based....TO COME BACK TO

   3. **From** - who the email is from, click on **Person** button ![Person button](images/person.png)

   4. **To** - who the email is to, click on the **Person** button ![Person button](images/person.png)and choose from the following options:

      ![Any user or partner mode](images/anygroups.png)

      - **Any user or partner** - if you choose this option, then click on **Users** and choose from Users, Groups or Partners and click into the field under **Select users** to see a dropdown list of users, predefined groups and partners and click onto your name of choice. You can add as many users, groups and partners as desired by clicking on a name in the list, or remove by clicking on the name within the field for example HR Team. 

        ![Clear user field](images/clearfield.png)
   
        In all modes you can clear a field by clicking on the field and click on **Clear field** ![Clear field](images/x.png).
   
      - **User(s) defined in a user field** - if you choose this option, meaning the user name is already defined in a form? TO COME BACK TO, then click on **User picker** button ![User picker button](images/userpicker.png) and click into the field under **Select a user field** to see a user picker field from a form, for example 'Line Manager' is within the form Employee Request
   
        ![Select a user field](images/userpickerfield.png)
   
        Click on the field to add to the list. You can add as fields as desired by clicking on the **User picker** button ![User picker button](images/userpicker.png)or remove a field by clicking on the field or by clicking on the **Bin/Trash** button. 
   
        ![User defined field](images/nameduserpicker.png)
   
        
   
      - **Form owner(s)** - if you choose this option, then click click into the field under **Form owner of selected form** and choose from the forms within that process.
   
        ![Form owner of selected form](images/formowners.png)
   
      - Email address in a field - if you choose this option, then click into the field under **Type the address or select from a field** and either type in an email address or choose from a field within a form within that process. TO COME BACK TO
      
        ![select email users](images/selectemailusers.png)
   
   In all cases when you have made your selection, click on  **OK** button ![OK button](C:\Kianda\docs-dev\rules\communications\send_email.assets\ok.png) when you are finished editing to save your changes or click on **Close** to exit the dialog box without saving.
   
   5. **CC** - same options as with **To** field.
   
   5. **BCC** - same options as with **To** field.
   
   5. **Subject** - type in your email subject and click on the **Ellipsis** button ![Ellipsis button](C:\Kianda\docs-dev\rules\communications\send_email.assets\ellipsis.png)to add an expression, see [Expressions](expressions.md) for more information. TO COME BACK TO
   
   5. **Body** - choose from an array of styles and formats to create your email including **Style,** **Colour**, **Font  size**, **Remove font style**, **Font family**, **Unordered list**, **Ordered list**, **Paragraph**, **Table**, **Link**, **Picture**, **Attach a File** and **Code view**. 
   
      ![Send email](images/email.png)
   
      For example if you click on **Code view** button ![Code view button](images/code.png)you can copy HTML code directly into the body text.
   
      Click on the the **Ellipsis** button ![Ellipsis button](images/ellipsis.png)to add an expression, see [Expression builder]#Expression builder for more details. 
   
   5. **Send via connector** - options are a) No or b) Yes - if you choose **Yes** then it means you can send via a datasource which is entered into the From field TO COME BACK TO for example a generic for your business like no-reply@greenitr.com for the company GreenITR.
   
   5. **Enable tracking** - options are a) No or b) Yes - if you choose **Yes** then you can track (read, receive) where? TO COME BACK TO



### Expression builder

The expression builder is a useful and efficient way to use existing form fields as part of automated emails that you want to send out.

For example if you have a form Annual Leave request that contains a text box field 'Employee Name' you can use this field in an automated email to let a set of managers know that an employee has submitted an a request. 

1. Click on the **Ellipsis** button ![Ellipsis button](images/ellipsis.png)beside email **Body** then the Expression builder dialog box opens.
2. Click into the field under **Add field to expression**. Forms and fields that are part of your process appear where you can expand elements to drill down to find the field that you want, for example 'Employee Name'.



![Expression builder](images/expressionaddfield.png)

The expression builder is useful to If you want to send a body email 

###### How to use
To send an email when the user submits a form:
1. Before adding the rule: 
   a. Add a name field to the current form: Click on Controls > Input > Text box and drag the field onto the form.  Edit the field by clicking on it and then clicking the pen icon. Change the Title to *Name*.  Change the Name(unique) to *name*.  
   b. Add an email address field to the current form: Click on Controls > Input > Text box and drag the field onto the form.  As before, change the Title to *Email address* and change the Name(unique) to *emailAddress*.  
2. Click on the Submit button.
3. Select Add a rule > Communications  > Send email.
4. Click on the person icon in the To: field.  Select Email address in a field and then you will be able to choose the text field with the email address which you added earlier.
5. Add some text to the Subject field. This field cannot be empty.
6. In the Body field, add some text: note that you can change the font size, add images etc.. 
7. Open the Expression builder (using the button on the right with three dots). Under Add field to expression, find the Name field which you added earlier.  Click on Add to expression.  You will see your name field listed as [name] in the Expression window.  Click OK.
8. Click OK to exit the rule. 

> **Warning** 
>
> If you add an email address to the From field then you must specify an Email connector.  See below.

###### Notes

**From:** If you leave this field empty (see example above), the email will be sent from noreply@kianda.com.  If you want your email to come from a different sender, follow these steps when you are editing the Send email rule:

1. Set Send via connector to Yes.  
2. Select an Email connector and click OK.

Note that this will override the global Email connector setting if one has been configured for your system.  Go to Administration > Subscription > Subscription Details to check for a global setting. 

**Filling in email addresses for the fields From: To: CC: and BCC: **
When you click on the person icon on the right hand side of one of these fields, you need to choose the Selection mode from the following options:
* Any user or partner: choose the user or partner (email address) from the Selected users list
* User(s) defined in a user field: choose the field where the user (email address) is stored
* Form owner(s): choose the form and the owner(s) (email address) will be selected
* Email address in field: either choose the field where the email address is stored or type in the email directly.

**Switching to HTML in the Body**
You can write text directly into the Body of the email.  If you want to view or edit the HTML, click on the Code View button (</>).  


**Attachments**: Files can be attached to the email.  First the file must be stored in a File field in one of the forms.  Open the Send Email rule and find the File icon in the Body field menu.  Click in the File field to find the field where the file is stored. Click on Insert attachment.  There is an option to attach a link to the file rather than the file itself.

**Enable tracking:** 

* This option allows you to track the email after it is sent. The following events are tracked: Open, Click, Bounce, or Spam.  
* The option is only available if Send via connector is set to No and the email is being sent from noreply@kianda.com. 
* If you click Yes to Enable tracking then you must have a field to store the event.  Select the field here.  