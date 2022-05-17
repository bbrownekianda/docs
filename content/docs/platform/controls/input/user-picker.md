---
title: "User picker control"
linkTitle: "User picker control"
weight: 8
typora-root-url: ..\..\..\..\..\static
---

The **user picker field** provides a way to associate a user to a particular task for example to allow a form user to find their manager to approve a workflow. This is achieved by connecting your Kianda form to a data source, for example information in SharePoint, and using the user picker field.



## How to get started

1. To add a particular user, click on **Controls** > **Input** > **User picker**. The field can also be placed within an element for example a panel, by clicking on the panel itself and then add user picker field. Compare in the image below, the field Line Manager which is inside a panel versus Department Manager which is outside the panel, both in the form Employee Request.

   ![User picker field inside and outside a panel](/images/userpickerinout.png)

2. Choose from the edit options:

   - **Title** - of the user, for example Training Manager

   - **Name** - this is a unique name for the field

   - **Help text** - information to help the form user

   - **Mode** - options are a) Single or b) Multiple 

      If you choose b) Multiple then you can choose the maximum number of users to select by clicking on the arrow or simply typing your number into the box, for example 3 users as shown below.

      ![Maximum number of users to select](/images/maxusers.png)

   - **Default to current user** - options to default to the current user when in edit mode are a) No or b) Yes

   - **Member of group** - select the group from your data source that the user is a member of, for example HR Managers

   - **Selection options** - choose from a) Users b) Groups c) Partners,  as many as needed

   - **Default selection option** - choose one from a) Users b) Groups c) Partners

   - **Show selection option menu** - options are a) No or b) Yes

3. Click on the **OK** button ![Ok button](/images/ok.png) when you are finished editing to save your changes or click on **Close** to exit the dialog box without saving.

4. If you need to re-edit the user picker field, click on the field itself and the **Pen** button ![Pen icon](/images/penicon.png) appears allowing you to edit the field.

   ![Editing the user picker field](/images/userpickeredit.png)

5. To move the field, click on the **Drag handle** ![Move button](images/move.png)on the user picker field itself and drag it to where you want it to appear on the form, for example within a panel. 

6. To save your changes to the form, click on the **Save** button ![Save button](/images/saveprocess.png).

3. To delete the field, click on the field itself and then click on the **Bin/Trash** button ![Bin or Trash icon](/images/binicon.png) and then click on **Ok** after you have reviewed the field name and are sure this is what you want to delete. Click on **Cancel** if you wish to cancel the deletion.



## How to edit user picker properties

To change the user picker field properties, click on the field itself and the properties pane appears on the right.

![User picker field properties](/images/userpickerproperties.png)

The **Field type**, User picker, is shown along with the **Title** of the field, in the example above Training Manager.

The options within properties are as follows, check the checkbox to implement:

- **Show Title** - show the title of the field
- **Required** - make this field mandatory for users to use
- **Enabled** - the field is enabled for users to use
- **Visible** - the field is visible to users
- **Layout** - change the width of the field by clicking on the bar in the Layout box until you see the desired size. Click on the arrow beside Layout to see the Mobile Layout and click on the bar to change the width of the text box for mobile use.

![Changing text box width](/images/textboxsize.png)

- **Rules** - rules for input fields are covered in [Rules](rules/README.md).
