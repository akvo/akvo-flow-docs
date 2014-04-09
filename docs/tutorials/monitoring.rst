Monitoring - tracking things over time
=======================================
Taking a survey of something, be it a water point, a tree, or a school, is usually a one-time thing. You collect data, analyse the data, take action, and that's it. But in many cases, you also want to go back at a later date, and do a follow-up: is this pump still working? Has the tree grown? Has that schools' latrine been repaired? This is what we call monitoring: observing facts about something, some 'entity' (machine, pump, person, etc), which has an identity and can be tracked over time. An identity is a set of attributes (id, serial number, name, etc) that *uniquely* identify an entity. 

The core idea of monitoring is to create 'records', to which information about a monitored entity can be added. Multiple survey forms can be created on the dashbaord, which together capture different aspects of a monitored entity. One form is used to create a new record, and the other forms are used to add additional information to an existing record. This can be visualised by comparing it with record files containing paper forms: a special 'registration' form creates the record file, and other forms can be added to an existing record file. 

 .. figure:: img-monitoring/1-monitoring.png
   :width: 500 px
   :alt: Illustration of monitoring
   :align: left

Existing records can be downloaded to the phone, so they can be updated with new information. On the phone, records can be searched by distance, id, or record name. The enumerator can either create a new record using the special registration form, or can add information to an existing record. The device can download records created by other enumerators. This makes it possible to capture how properties of the entity change over time, or to collect new properties.

This tutorial shows how a monitoring project is set up, and how the monitoring features work on the FLOW dashboard and the FLOW app. We start by introducting a real-life example.

.. container:: clearer

    .. image:: /img/spacer.png

Real-life examples
------------------
A municipality in a large city manages a set of 40.000 water meters, which need to be visited every 4 months. Each water meter has an identification number, and an address. 

They want to use different forms to collect data on the water meters: a *register new water meter* form, that is filled in with customer information and the meter id when a new water meter is registered, a *current meter reading* form, which is used to capture a reading plus an image of the meter, and a 'decomission water meter' form, which is filled in when a water meter is broken, or closed off. 

The enumerators need to be able to see a list of watermeters on their device based on proximity, and to be able to filter on name or street. On the dashboard, the financial department wants to be able to export a list of all customers with the current meter readings, so they can prepare the bills. 

Monitoring - Dashboard
-----------------------
Creating a monitoring project
++++++++++++++++++++++++++++++
A monitoring project consists of a set of survey forms. To create a monitoring project, follow these steps:

1. Start by creating a new survey group on the survey tab, and select it after it has been created. 

2. Click the blue 'Make monitoring group' button on the top. After accepting the popup notification, this will change to 'Monitoring Enabled', and show a dropdown where you can select one of the surveys in this group as the survey that creates new monitored entities. As we don't have any surveys yet, this dropdown is still empty.

3. Create the surveys you need, just as you would create normal surveys. In the survey that will be used to create new records, there are two checkboxes which are important. 
   a. The first one is *Use in record display*, which is shown on free text questions. When this is checked, the answer to this question will become part of the 'name' of the record. This will be shown in lists on the device, and can be used to search records. By default, this is off. This should only be enabled for one or two questions which will help to identify the record, such as an id, or a name. Multiple values will be added together separated by a dash '-'.
   b. The second one is *Use as record location*, which is shown on geolocation questions. When this is checked, the location captured by this question will be used as the main location of the record. By default, this is turned on.

 .. figure:: img-monitoring/2-monitoring.png
   :width: 500 px
   :alt: Illustration of monitoring
   :align: left

4. Publish the surveys

5. After the surveys are created, select one of them using the dropdown box in the survey group overview. This survey gets the special role of 'registration survey', and is capable of creating new records on the phone.

.. container:: clearer

    .. image:: /img/spacer.png

Structuring your survey forms
++++++++++++++++++++++++++++++
Because you can use different forms to collect data on a record, the question comes up what questions to ask in which forms. The guideline to follow is this:

* Information captured once - Information that identifies the entity you are monitoring should go in the survey that creates the record. For example, if you monitor a water meter, you would create a 'water meter registration' form, which captures the name of the owner, his/her address, and the meter id. Not more.

* Information tracked over time — Information about the entity that will probably change, and that you want to track over time, should go in a different form. For example, you might have a 'water meter reading' form, which just captures the current water meter reading and a photo of the water meter. Or, if you are monitoring patients in a hospital, you could have 'blood test', and 'psychological test' forms. 

Viewing record data
++++++++++++++++++++
To see which records are available for a monitoring project, open the 'Monitoring' subtab on the 'Data' tab. There, you can select the survey group that contains the monitoring project, and you will see a table with the records within that project. The table shows 'identifier', 'display name', and 'last update'. The identifier is the unique identifier of the record. The display name is derived from answers to questions in the 'registration' form. The setting 'display in record list on device' on free text questions determines if answers to that question become part of the display name.

 .. figure:: img-monitoring/3-monitoring.png
   :width: 800 px
   :alt: Illustration of monitoring
   :align: center

When you click 'view details' on any one of the records in the table, you will see the survey responses that are part of a single record. For each submitted survey response, the survey, submitter, device, and collection data are displayed.

When you click 'view details' on a survey response, you will see the individual answers given to the questions in that response.

Exporting record data
++++++++++++++++++++++
To export data, go to the 'Reports' tab, and select the 'Export reports' subtab. Here, you can select a survey group and survey form, and . If you select a survey group that is also a monitored group, a checkbox 'Export only last collection' will be displayed. When this is enabled, only the latest collected data for that survey will be exported. For example, if you have collected water several meter readings for a single water meter, and this checkbox is selected, only the last one will be exported. 

 .. figure:: img-monitoring/4-monitoring.png
   :width: 800 px
   :alt: Illustration of monitoring
   :align: center

The exported file will contain the record identifier and the display name as the first two columns. 

In a real-life situation, you might want to export a report which combines answers from different forms. For example, if you are monotoring water meters, you might want to export a file which has the customer name and address, plus the latest value of the water meter reading. At the moment, this type of exporting is not yet possible, but it will be made available in a future version of FLOW.

In the mean time, you can use an excel technique to match data accross different files, based on the identifier of each record. This uses the VLOOKUP function, as described `in this article <http://howtovlookupinexcel.com/vlookup-between-two-workbooks>`_  and `this instruction movie <https://www.youtube.com/watch?v=809m6kLTfgI>`_. If you need help in implementing this, please contact us as support@akvoflow.org


Monitoring - FLOW app
----------------------
 .. figure:: img-monitoring/5-monitoring.png
   :width: 200 px
   :alt: Illustration of monitoring
   :align: left

When the app is opened for the first time, it will sync with the server and display the survey groups that contain surveys that have been assigned to the device. Normal survey groups just contain surveys, which can be used to collect data as usual. A survey group which is also a monitoring group is different: it contains both the records for a monitored entitiy, and the survey forms which are used to create new forms or add additional information to them.



.. container:: clearer

    .. image:: /img/spacer.png

Syncing records
++++++++++++++++++++++
To sync records, first make sure that you have a good wifi or 3G connectivity. Downloading a large number of records can involve quite some data, which is why it is important to have a good connection. If you sure the connection is ok, follow these steps:

1. Select the monitoring group that you want to work with.

2. Click on the 'more' button in the top right (three vertical dots), and select 'Sync records'

3. The records will be synced, and a message in the notification bar will show the progress and how many records have been synced.

 .. figure:: img-monitoring/6-monitoring.png
   :width: 1000 px
   :alt: Illustration of monitoring
   :align: center

The syncing process is optimised to only download the latest information — any records that have not changed since the last download will not be downloaded again.

Syncing records is not an automatic process, so it needs to be manually performed whenever the enumerator needs the latest updates from the server.

Creating a new record
++++++++++++++++++++++
A new record can be created by clicking the '+' icon, which is shown on the top of the list of records. When a new record is first created, only the special 'registration' form can be selected. This is needed to capture the identifying information for the new record. When this first form has been submitted, other forms become available.

 .. figure:: img-monitoring/7-monitoring.png
   :width: 1000 px
   :alt: Illustration of monitoring
   :align: center

Searching for an existing record
+++++++++++++++++++++++++++
To find a record, follow one of these steps:

1. By default, the list of records is sorted by distance, with the nearest record shown first. For this to work, the GPS of the phone needs to be active. To select a record, click it. By clicking the 'more' icon (three vertical dots) and selecting 'order by', you can also order the records by date, with the most recently changed first.

2. By clicking the 'map' tab, a map is shown with all the records, centered on your present location. If you click a record marker it will show the display name and the identifier. If you click that text, the record will be selected.

3. If you click the 'search' icon and start typing, a list of filtered records will be shown. The text you type is compared to both the display text and the identifier. 

 .. figure:: img-monitoring/8-monitoring.png
   :width: 600 px
   :alt: Illustration of monitoring
   :align: center

Adding information to an existing record
+++++++++++++++++++++++++++++++++++++++++
When you have selected a record, the record display name and identifier are displayed, plus a list of available surveys. To add information to the selected record, select a survey, fill it, and submit it.

If the record already contains a previous filled-in version of that survey, the phone will prompt the user if he/she wants to prefill the new, empty survey with the previously collected values. If the users selects 'ok', a fresh copy of the survey is opened, with the previous values filled in. 

 .. figure:: img-monitoring/9-monitoring.png
   :width: 1000 px
   :alt: Illustration of monitoring
   :align: center

It is important to understand that the previous values will not be overwritten — only new information will be added. This is true in general: only new facts are created and stored, old values are never overwritten. This protects data against human error.

Updating information collected by the 'registration' form
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 .. figure:: img-monitoring/10-monitoring.png
   :width: 300 px
   :alt: Illustration of monitoring
   :align: left

Usually, the registration form is only used once, when the record is first created. That is why that survey is shown in a different (red) color.

However, sometimes data collected by this survey needs to be updated, for example in the case of a spelling mistake. That is why the survey can still be accessed. When the enumerator clicks this survey, a warning message is displayed. When the enumerator accepts this, they can prefill the survey with the existing values, and update them by making the required changes and submitting the survey.