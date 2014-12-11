Monitoring - tracking things over time
=======================================
Taking a survey of something, be it a water point, a tree, or a school, is usually a one-time event. You collect data, analyse the data, take action, and that's it. But in many cases, you also want to go back at a later date, and do a follow-up: is this pump still working? Has the tree grown? Has that schools' latrine been repaired? This is what we call monitoring: observing facts about something, some 'entity' (machine, pump, person, etc), which has an identity and can be tracked over time. An identity is a set of attributes (id, serial number, name, etc) that *uniquely* identify an entity. 

The core idea of monitoring is to create 'data points', to which information about a data point can be added. Multiple survey forms can be created on the dashboard, which together capture different aspects of a data point. One form is used to create a new data point, and the other forms are used to add additional information to an existing data point. This can be visualised by comparing it with record files containing paper forms: a special 'registration' form creates the record file, and other forms can be added to an existing record file. 

 .. figure:: img-monitoring/1-monitoring.png
   :width: 500 px
   :alt: Illustration of monitoring
   :align: left

Existing data points can be downloaded to the mobile device, so they can be updated with new information. On the device, data points can be searched by distance, id, or data point name. The enumerator can either create a new data point using the special registration form, or can add information to an existing data point. The device can download data points created by other enumerators. This makes it possible to capture how properties of the entity change over time, or to collect new properties.

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

To add multiple forms to a survey, you first need to enable monitoring on the survey. First go to the survey basics, and select 'Show advanced settings'.

 .. figure:: ../dashboard/img/2-show_advanced.png
   :width: 200 px
   :alt: image of dashboard
   :align: center 

Next, you can check the checkbox 'Enable monitoring features'. When this has been enabled, you can create multiple forms. In addition, you need to select the form which will be used to create new data points. Other forms will just be able to update existing data points. Please refer to :doc:`./7-monitoring-features` for further details.


 .. figure:: ../dashboard/img/2-survey_enable_monitor.png
   :width: 200 px
   :alt: image of dashboard
   :align: center 

   Enabling monitoring on a survey.

 .. figure:: ../dashboard/img/2-extra_form.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   You can now add additional forms to the survey.

Next step is to create the forms you need, just as you would create normal surveys. In the form that will be used to create new data points, there are two checkboxes which are important. 
   a. The first one is *Use in data point display*, which is shown on free text questions. When this is checked, the answer to this question will become part of the 'name' of the data point. This will be shown in lists on the device, and can be used to search data points. By default, this is off. This should only be enabled for one or two questions which will help to identify the data point, such as an id, or a name. Multiple values will be added together separated by a dash '-'.
   b. The second one is *Use as data point location*, which is shown on geolocation questions. When this is checked, the location captured by this question will be used as the main location of the data point. By default, this is turned on.

4. Publish the survey forms by clicking the 'publish survey' button

5. After the surveys are created, select one of them using the dropdown box in the survey group overview. This survey gets the special role of 'registration survey', and is capable of creating new data points on the device.

.. container:: clearer

    .. image:: /img/spacer.png

Structuring your survey forms
++++++++++++++++++++++++++++++
Because you can use different forms to collect data on a data point, the question comes up what questions to ask in which forms. The guideline to follow is this:

* Information captured once - Information that identifies the entity you are monitoring should go in the survey that creates the data point. For example, if you monitor a water meter, you would create a 'water meter registration' form, which captures the name of the owner, his/her address, and the meter id. Not more.

* Information tracked over time — Information about the entity that will probably change, and that you want to track over time, should go in a different form. For example, you might have a 'water meter reading' form, which just captures the current water meter reading and a photo of the water meter. Or, if you are monitoring patients in a hospital, you could have 'blood test', and 'psychological test' forms. 

Viewing data point data
++++++++++++++++++++
To see which data points are available for a monitoring project, open the 'Monitoring' subtab on the 'Data' tab. There, you can select the survey group that contains the monitoring project, and you will see a table with the data points within that project. The table shows 'identifier', 'display name', and 'last update'. The identifier is the unique identifier of the data point. The display name is derived from answers to questions in the 'registration' form. The setting 'display in data point list on device' on free text questions determines if answers to that question become part of the display name.

 .. figure:: img-monitoring/3-monitoring.png
   :width: 800 px
   :alt: Illustration of monitoring
   :align: center

When you click 'view details' on any one of the data points in the table, you will see the survey responses that are part of a single data point. For each submitted survey response, the survey, submitter, device, and collection data are displayed.

When you click 'view details' on a survey response, you will see the individual answers given to the questions in that response.

Exporting data point data
++++++++++++++++++++++
To export data, go to the 'Reports' tab, and select the 'Export reports' subtab. Here, you can select a survey group and survey form, and . If you select a survey group that is also a monitored group, a checkbox 'Export only last collection' will be displayed. When this is enabled, only the latest collected data for that survey will be exported. For example, if you have collected water several meter readings for a single water meter, and this checkbox is selected, only the last one will be exported. 

 .. figure:: img-monitoring/4-monitoring.png
   :width: 800 px
   :alt: Illustration of monitoring
   :align: center

The exported file will contain the data point identifier and the display name as the first two columns. 

In a real-life situation, you might want to export a report which combines answers from different forms. For example, if you are monotoring water meters, you might want to export a file which has the customer name and address, plus the latest value of the water meter reading. At the moment, this type of exporting is not yet possible, but it will be made available in a future version of FLOW.

In the mean time, you can use an excel technique to match data accross different files, based on the identifier of each data point. This uses the VLOOKUP function, as described `in this article <http://howtovlookupinexcel.com/vlookup-between-two-workbooks>`_  and `this instruction movie <https://www.youtube.com/watch?v=809m6kLTfgI>`_. If you need help in implementing this, please contact us as support@akvoflow.org


Monitoring - FLOW app
----------------------
 .. figure:: img-monitoring/5-monitoring.png
   :width: 200 px
   :alt: Illustration of monitoring
   :align: left

When the app is opened for the first time, it will sync with the server and display the survey groups that contain surveys that have been assigned to the device. Normal survey groups just contain surveys, which can be used to collect data as usual. A survey group which is also a monitoring group is different: it contains both the data points for a monitored entitiy, and the survey forms which are used to create new forms or add additional information to them.



.. container:: clearer

    .. image:: /img/spacer.png

Syncing data points
++++++++++++++++++++++
To sync data points, first make sure that you have a good wifi or 3G connectivity. Downloading a large number of data points can involve quite some data, which is why it is important to have a good connection. If you sure the connection is ok, follow these steps:

1. Select the monitoring group that you want to work with.

2. Click on the 'more' button in the top right (three vertical dots), and select 'Sync data points'

3. The data points will be synced, and a message in the notification bar will show the progress and how many data points have been synced.

 .. figure:: img-monitoring/6-monitoring.png
   :width: 1000 px
   :alt: Illustration of monitoring
   :align: center

The syncing process is optimised to only download the latest information — any data points that have not changed since the last download will not be downloaded again.

Syncing data points is not an automatic process, so it needs to be manually performed whenever the enumerator needs the latest updates from the server.

Creating a new data point
++++++++++++++++++++++
A new data point can be created by clicking the '+' icon, which is shown on the top of the list of data points. When a new data point is first created, only the special 'registration' form can be selected. This is needed to capture the identifying information for the new data point. When this first form has been submitted, other forms become available.

 .. figure:: img-monitoring/7-monitoring.png
   :width: 1000 px
   :alt: Illustration of monitoring
   :align: center

Searching for an existing data point
+++++++++++++++++++++++++++
To find a data point, follow one of these steps:

1. By default, the list of data points is sorted by distance, with the nearest data point shown first. For this to work, the GPS of the device needs to be active. To select a data point, click it. By clicking the 'more' icon (three vertical dots) and selecting 'order by', you can also order the data points by date, with the most recently changed first.

2. By clicking the 'map' tab, a map is shown with all the data points, centered on your present location. If you click a data point marker it will show the display name and the identifier. If you click that text, the data point will be selected.

3. If you click the 'search' icon and start typing, a list of filtered data points will be shown. The text you type is compared to both the display text and the identifier. 

 .. figure:: img-monitoring/8-monitoring.png
   :width: 600 px
   :alt: Illustration of monitoring
   :align: center

Adding information to an existing data point
+++++++++++++++++++++++++++++++++++++++++
When you have selected a data point, the data point display name and identifier are displayed, plus a list of available surveys. To add information to the selected data point, select a survey, fill it, and submit it.

If the data point already contains a previous filled-in version of that survey, the mobile device will prompt the user if he/she wants to prefill the new, empty survey with the previously collected values. If the users selects 'ok', a fresh copy of the survey is opened, with the previous values filled in. 

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

Usually, the registration form is only used once, when the data point is first created. That is why that survey is shown in a different (red) color.

However, sometimes data collected by this survey needs to be updated, for example in the case of a spelling mistake. That is why the survey can still be accessed. When the enumerator clicks this survey, a warning message is displayed. When the enumerator accepts this, they can prefill the survey with the existing values, and update them by making the required changes and submitting the survey.
