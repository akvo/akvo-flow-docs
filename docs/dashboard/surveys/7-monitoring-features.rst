Monitoring - tracking things over time
--------------------------------------

Taking a survey of something, be it a water point, a tree, or a school, is usually a one-time event. You collect data, analyse the data, take action, and that's it. But in many cases, you also want to go back at a later date, and do a follow-up: is this pump still working? Has the tree grown? Has that schools' latrine been repaired? This is what we call monitoring: observing facts about something, some 'entity' (machine, pump, person, etc), which has an identity and can be tracked over time. An identity is a set of attributes (id, serial number, name, etc) that *uniquely* identify an entity. 

The core idea of monitoring is to create 'data points', to which information about a data point can be added. Multiple survey forms can be created on the dashboard, which together capture different aspects of a data point. One form is used to create a new data point, and the other forms are used to add additional information to an existing data point. Also see :doc:`../../tutorials/monitoring` for the whole story on how to use monitoring.

Creating a monitoring project
++++++++++++++++++++++++++++++
A monitoring project consists of a set of survey forms. A special survey group is used to hold the forms together. To create a monitoring project, follow these steps:

1. Start by creating a new survey group on the survey tab, and select it after it has been created. 

2. Click the blue 'Make monitoring group' button on the top. After accepting the popup notification, this will change to 'Monitoring Enabled', and show a dropdown where you can select one of the surveys in this group as the survey that creates new data points. As we don't have any surveys yet, this dropdown is still empty. The survey group is shown with an 'M' in front of it, to show it is a monitoring group.

3. Create the surveys you need, just as you would create normal surveys. In the survey that will be used to create new data points, there are two checkboxes which are important. 
   a. The first one is *Use in data point display*, which is shown on free text questions. When this is checked, the answer to this question will become part of the 'name' of the data point. This will be shown in lists on the device, and can be used to search data points. By default, this is off. This should only be enabled for one or two questions which will help to identify the data point, such as an id, or a name. Multiple values will be added together separated by a dash '-'.
   b. The second one is *Use as data point location*, which is shown on geolocation questions. When this is checked, the location captured by this question will be used as the main location of the data point. By default, this is turned on.

 .. figure:: ../img/2-monitoring.png
   :width: 500 px
   :alt: Illustration of monitoring
   :align: left

4. Publish the surveys

5. After the surveys are created, select one of them using the dropdown box in the survey group overview. This survey gets the special role of 'registration survey', and is capable of creating new data points on the device.

.. container:: clearer

    .. image:: /img/spacer.png

Structuring your survey forms
++++++++++++++++++++++++++++++
Because you can use different forms to collect data on a data point, the question comes up what questions to ask in which forms. The guideline to follow is this:

* Information captured once - Information that identifies the entity you are monitoring should go in the survey that creates the data point. For example, if you monitor a water meter, you would create a 'water meter registration' form, which captures the name of the owner, his/her address, and the meter id. Not more.

* Information tracked over time — Information about the entity that will probably change, and that you want to track over time, should go in a different form. For example, you might have a 'water meter reading' form, which just captures the current water meter reading and a photo of the current water meter reading.  