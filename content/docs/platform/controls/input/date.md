---
title: "Date control"
weight: 1
typora-root-url: ..\..\..\..\..\static
---

**Date controls** or **Date fields** can be inserted in a form when you want a user to be able to input a date and time by using a date and time picker. For example, in a Training Request form, you may want the user to select the date and time of the training course they want to attend.

## How to get started

1. To add a **Date field** to a form, first open the relevant process. Then select the form within that process that you want to add the field to (so that the **Edit Form** button ![Edit form button](/images/penicon.png) is visible). 


2. Insert the **Date field** by clicking on **Controls** in the left-hand pane to expand the Controls menu, then select **Input** to view the range of Input controls and click on **Date**. A date field will be added to your form with the default title of '**Date 1**' and a pop-up message will say 'Field added'.

   ![List inside and outside a panel](/images/date-field-added.jpg)
   
3. The Date field has a small calendar icon on the right hand side - when the user clicks on this icon a calendar is displayed, allowing them to select a date.

   ![List inside and outside a panel](/images/date-field-expanded.jpg)
   
### How to edit, move and delete Date fields

To edit a **Date field**, select the field (by either clicking on the field title or on the field's **Drag handle** button ![Drag handle button](/images/draghandlewhite-frame.png)) and then click on the **Edit field** button (Pen icon) ![Edit field button](/images/penicon.png). 

![Select date field to edit](/images/select-date-field-to-edit.jpg)

The **Edit field** dialog box will open, enabling you to choose from a range of options.

![Edit date field dialog box](/images/edit-date-field-dialog-box.jpg)

The options within the **Edit date field dialog box** include:

- **Title** - you can change the title of the date field

- **Help text** - you can insert help text a user can view when completing the date field. If you add help text, a question mark ![Help text icon](/images/help-icon.jpg) icon will appear next to the field title and, if the user clicks on this, they will see the help text you have inserted.

- **Display format** - you can choose whether the date field shows the date only or the date and time

- **Adjust to user timezone** - you can select this if you want the date field to adjust to the time zone of the form user

- **Set default date onload** - if you choose 'Yes', this means that the date field will automatically be populated (with a date stamp) when a user opens the form to start completing it; by default, the date that will be inserted is today's date. If you choose 'No', then the user will need to manually complete the date field. 
  
  If you choose 'Yes', two additional options then appear in the dialog box: 

  - 1. **Default date** - this is where you can choose the default date that will be automatically inserted in the form when a user opens it. You can choose from '**Now**', '**Today**' (which inserts today's date and a time of 00:00 midnight) or '**Relative from now'** (you can insert the date you want to use, in terms of the number of days, hours and minutes from now).
  - 2. **Always set date even if not empty** - if you select this option, this means that the default date you've chosen to be automatically inserted when a user opens the form will be updated/changed *each time* the user goes into the form. In other words, the initial date that was inserted when the form was first opened will be replaced/updated when the user goes back into the form. If you want the date field to retain the initial date the user started to complete the form, do not tick this checkbox.
  
- **Enable native picker on mobile** - you can choose to allow users who are completing the date field on a mobile phone to use the default pop-up date picker associated with their mobile phone

To move a **Date field**, simply select the field's **Drag handle** button ![Drag handle button](/images/draghandlewhite-frame.png) and drag and drop the field wherever you want to move it to within your form.

![Date field drag handle](/images/move-date-field-drag-handle.jpg)

To delete a **Date field** from your form, simply select the field (by either clicking on the field's name or its **Drag handle** button ![Drag handle button](/images/draghandlewhite-frame.png)), click on the **Bin/Trash** button ![Bin icon](/images/binicon.png) and then click on **OK** to confirm.

### How to edit Date field properties ###
To view or edit the field properties associated with a **Date field**, select the field (by clicking on the field title or field drag handle button ![Drag handle button](/images/draghandlewhite-frame.png)) - the **Field properties** menu will appear in the right-hand pane.

![Field properties](/images/date-field-properties-new.jpg)

In the example shown here, a **Date field** titled **Date** has been selected in a form called 'Expense Report' and the Field properties associated with this field include its Title, that its title will be shown in the form (the 'Show title' checkbox is ticked), that this will not be a field users are required to complete (the 'Required' checkbox is not selected), that this field will be enabled for users to complete (the 'Enabled' checkbox is ticked), and that this field will be visible to form users (the 'Visible' checkbox is ticked).

To learn more about the different options within the Field properties menu, go to [Field Properties](/docs/platform/controls/properties#field-properties).

### Saving changes and version history ###
Make sure to save any changes you make by clicking on the **Save** button ![Save](/images/saveprocess.png). You will always have the option to revert back to previous versions of your form by clicking the **Design Version History** ![Version button](/images/version8.png) button in the top right corner.



### What's next  ![Idea icon](/images/18.png) ###

Now that you've learned about **Date controls**, find out more about the other types of **Input fields** you can add to a Kianda process:

- [File upload control](/docs/platform/controls/input/file-upload/)
- [List control](/docs/platform/controls/input/list/)
- [Number control](/docs/platform/controls/input/number/)
- [Table control](/docs/platform/controls/input/table/)
- [Textbox control](/docs/platform/controls/input/textbox/)
- [Toggle control](/docs/platform/controls/input/toggle/)
- [User picker control](/docs/platform/controls/input/user-picker/)