# Connect your data #

Connecting your data to Kianda processes, allows real-time scalability, so as your organisation grows, the processes you have created continue to perform, providing sustainable, flexible growth. Your data may be held in **datasources** like SharePoint, Salesforce or SAP. Kianda comes with 19 predefined [**data connectors**](connectors/readme.md), allowing you to connect to these datasources.  

If you are a developer and want to connect to a datasource that is not included in the predefined set, you can use SOAP or REST to create your own API for data transfer.

Connecting to data happens during the **process design** phase, see image below.

***Design process***

![Designing in Kianda](images/highlightdesign.png)

You can set up data connectors first, before building your process if you wish, and then link those data connectors when [adding controls and rules](getting-started/add_form_elements.md).

The video below highlights how to connect to a datasource, in this example, SharePoint and [How to get started](#how-to-get-started.md) runs through the process in steps including an example of how to use this datasource in a list field.

<video width="100%" style="width:100%" controls>
    <source src="../videos/SharePoint connection.mp4">
    Your browser does not support the video tag.
    </source>
</video>



## How to get started ##

In this example, we will connect to a SharePoint list called 'Types of Training'. We will then show how to add a list field to a form to use the information from the data connector.

1. To connect to a datasource, go to the **Side menu** > **Administration** > **Data sources**.

1. Click on **+ Add new** button ![Add new data connector button](images/addnew.png) and **SharePoint**.

1. Fill out Site URL and choose from options like SharePoint Online, if its a Site or Site Collection and Authentication mode.

   ***Connecting to SharePoint***

   ![Sharepoint details](images/sharepoint.png)

1. Click on **Test connection** and then **Save**.

1. From here we can add a list field called Type of Training, and choose **Data source** as a List source.

***Edit field dialog box***

![SharePoint list example](images/traininglist.png)

6. Click on the **Datasource** button ![Datasource button](images/datasource.png) and choose the appropriate datasource, in this case a SharePoint list called Training Site. Choose the appropriate **Display field**, **Value field** and choose a field to **Sort by**.
7. The result is a dropdown list called Types of training which is available for use in our Training Request Form. 
7. When your form is complete, click on the **Save** button to save your work.

The end result is a complete process that is ready for test and review. Make sure to click on the **Save** button ![Save button](images/save.png) to save your work. Go to [Preview the design](getting-started/previewer.md) to find out how to perform these steps.



### What's next  ![Idea icon](images/18.png) ###

The next steps are: 

- [**Preview the design**](getting-started/previewer.md)
- [**Publish your process**](getting-started/publish_process.md)




### **To return to the previous pages click on the links below**  ![Lighting icon](images/10.png) 

- [**Design and build your process**](getting-started/design_process.md) 

- [**Add forms**](getting-started/create_form.md)

  