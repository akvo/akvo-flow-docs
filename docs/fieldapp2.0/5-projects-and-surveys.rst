Projects and Data Points
========================

Projects
--------

Unlike previous versions of the Akvo FLOW app, surveys are now grouped into projects, which act as containers to group surveys with a similar nature. All available projects are presented in the main screen of the app, and are automatically created when synchronising surveys into the device (more on survey synchronisation later). In order to interact with a project, **you must have a user selected**. Please, refer to the *Manage Users* section to learn how to create and select users.


*Insert project list screenshot here*
   
   Every synced project will be available in the home screen of the app


To select a project, click on its name, and the list of available *Data Points* will be displayed.

*Insert Data Points tab screenshot*
    
   Selecting a project allows us to browse all its collected Data Points

When a project is opened for the first time, no Data Point is available yet, and we need to create them manually. For this, click on the **CREATE NEW DATA POINT** button, and a new Data Point will be created.

We can sort the Data Point list by clicking the *Order By* icon, and selecting the desired criteria.

*Insert order by screenshot*

We can also see an overview of the data collection statistics, by clicking the *Project Stats* icon

*Insert stats screenshot*

Data Points
-----------

A Data Point contains all the information collected for a particular *entity*. Some Data Points hold more than one survey, and all their responses will be part of the same Data Point. This is particularly useful when the goal is to track data changes over time, and a given point needs to be checked out on a periodical basis. This allows us to effectively relate survey responses to the same point, even collecting multiple responses of the same survey.

Each Data Point has a unique identifier, along with a meaningful name (automatically created based on survey responses) and a geolocation. To select a Data Point, click on its row in the *Data Points* tab, or browse the *Map* tab to find it. You can alternatively use the *search* functionality, simply clicking the search icon and typing the Data Point name or ID.

*Insert map tab screenshot*

// Before we dive into surveys, we need to make a subtle difference between the two types of Data Points we might find in the app.

Monitored Data Points
^^^^^^^^^^^^^^^^^^^^^

A monitored Data Point is one that contains multiple surveys within it. Typically, one of this surveys will be the *Registration form*, which will collect basic data about the entity being surveyed. This normally involves collecting the name, location, etc -- In essence, attributes that **do not** change over time. All surveys responded in a Monitored Data Point will be appended to the history tab. This will let us browse any data collected for a particular point.

*Insert history tab screenshot*

Monitored Data Points can be synchronised, downloading in the device any previously collected Data Point for a particular project, and adding new responses to them. This means that one device can create a new Data Point, adding a few responses, and once the data is sent to the server, a different device can download the Data Point and keep adding data to it.

To synchronise all Data Points collected in a project, click on the *Sync Data Points* icon. Note that you will need a reliable internet connection to perform this action.

*Insert sync icon screenshot*

Synchronisation progress is displayed in an ongoing notification. You can draw dawn the status bar in the device to see the progress.

*Insert sync screenshot*

Once the synchronisation is finished, the notification will show the total amount of Data Points synced.

*Insert sync finished screenshot*

Non-monitored Data Points
^^^^^^^^^^^^^^^^^^^^^^^^^

Non-monitored Data Points behave pretty much like the monitored ones, except with one difference: they only contain one survey. Furthermore, Projects holding non-monitored Data Points cannot be synchronised. Only locally collected data will be available in the device.

From within a Data Point, we have access to *Forms*, *History*, and *Map* tabs, which represent survey definitions, responses, and point location, respectively.

Forms
^^^^^

*Note: 'Form' and 'Survey' are equivalent terms, and can be used interchangeably.*

**Forms** tab contains the forms for a particular Data Point. Given the aforementioned description, we may encounter many forms (monitored Data Point), or a single one (non-monitored Data Point).

*Insert forms tab screenshot*

History
^^^^^^^
A big difference between the old and the new app, is how collected data is reviewed in the device.

History contains all the form responses for the given Data Point. From this tab, we can resume an ongoing form, or review an already submitted one, by clicking the corresponding item in the list.

This tab is particularly useful to check the **form status**, which is displayed next to each form. A form response can have the following statuses:

* **Saved:** This form is not submitted yet, and can be resumed in order to add more answers.
* **Exported:** This form is submitted and exported in the SD card, but the device has not synchronised it with the dashboard. As soon as an Internet connection is available, it will be sent.
* **Synced:** This form is submitted and fully synchronised with the dashboard.

*Insert history tab screenshot*

Map
^^^

Map tab allows us to locate the Data Point in the map. Note that for this to happen, the *registration form* must have been answered, providing its latitude and longitude coordinates.

*Insert map tab screenshot*

