Data collection structure
=========================

Surveys are used to collect data on a particular subject. Each survey consists of one or multiple forms. Each form contains a series of questions and the questions are organized into question groups. 

.. _surveys:

Surveys
-------

Each survey consists of one or multiple forms. A regular survey consists of only one form. However, if monitoring is enabled, your survey will hold multiple forms. For more details on surveys check the chapters explaining surveys in the dashboard, The Dashboard - Surveys http://flow.readthedocs.org/en/latest/docs/dashboard/2-surveys.html

.. _ select_a_survey:

Select a survey
~~~~~~~~~~~~~~~

In order to start your data collection work, you need to select a survey. In the side menu you see a list of all surveys that have been assigned to your device. To select a survey, click on its name. 

You are now in the **data point list** for your selected survey. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10332403/367d66d2-6cdd-11e5-9718-810cbc0b8131.jpg
   :width: 200 px
   :alt: image of phone
   :align: center

These are the different parts of this screen and their functions: 

   1. **Menu icon**, which brings you back to the side menu.
   2. The **selected survey name** is displayed in the top header of your screen.
   3. To start collecting data, click on the **+** icon. With this icon you create a new data point.
   4. **Overflow icon**. This icon brings you to a small menu via which you can search for a specific data point, sort your list of data points, check statistics on your data collection and synchronise data points for a monitoring survey. 
   5. There are two tabs through which you can navigate: **Data points** (5a) and **Map** (5b). The Data points tab is selected by default and shows all your points in a list. The Map tab shows where your data points are located on the map, if location data is available.
   6. **Data point list**. For more details check **Data points** below.


When a survey is opened for the first time, no data points are visible yet. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302566/cee1568e-6c0d-11e5-8ce9-637c3df4d457.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *A selected survey with no data submitted.*

.. _data_points:

Data points
-----------

A data point contains all the information collected for a particular something, such as a water point, school, or farmer. Some data points hold more than one form, and all the filled forms are part of the same data point. This is particularly useful when the goal is to track data changes over time, and a given point needs to be monitored periodically. 

Each data point has a name created based on answers to selected questions. In the Dashboard, you can specify which questions are used to construct the data point name. Following the name you see a unique identifier. The data point identifier consists of random numbers and letter and is generated automatically. You can see when the data point was submitted or last modified. The icon represents the status of the data point and its meaning is explained as well. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302574/d607d988-6c0d-11e5-8195-ca06efcd1ce3.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Data point details*

.. _creating_a_new_data_point:

Creating a new data point
~~~~~~~~~~~~~~~~~~~~~~~~~

To create a new data point and start your data collection click on the **+** icon. 

If you are collecting data for a non-monitoring survey, the '+' icon will bring you directly into the form and you can fill in the questions. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302659/76722072-6c0e-11e5-99c9-cce3cb9e8f14.jpg
   :width: 400 px
   :alt: image of phone
   :align: center
   
   *The workflow when collecting data for a non-monitoring survey.*


If you are collecting data for a monitoring survey, the '+' icon will bring you into the data point, where you have two tabs to select from, the Forms tab and History tab. The Forms tab lists all the forms within your survey. For a new data point you can only select a single form, which is defined as the registration form. After selecting the registration form  you can fill in the data. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302685/9d16b616-6c0e-11e5-8765-c9d2c7bd7ed0.jpg
   :width: 600 px
   :alt: image of phone
   :align: center
   
   *The workflow when collecting data for a survey with monitoring enabled.*

.. _selecting_a_data_point:

Selecting a data point
~~~~~~~~~~~~~~~~~~~~~~

To select a data point, click on it in the **Data Points tab**, or browse the **Map tab** to find it. Clicking on a marker on the map will show you the name and id of the datapoint. Clicking on that name will take you to the datapoint. You can alternatively use the Search functionality located under the overflow icon. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302688/a931a0d2-6c0e-11e5-8516-d9234b691dc7.jpg
   :width: 200 px
   :alt: image of phone
   :align: center

.. _sorting_the_list_of_data_points:

Sorting the list of data points
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can sort the data point list as well. By default the data points are ordered by date, where the latest data point is placed on the top of the list. Click on the overflow icon in the top right corner of your screen and select **Sort**. You can sort the data points order by date, distance from your current location, upload status and name. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302692/b54f344c-6c0e-11e5-9c5b-ae7789dd6ab8.jpg
   :width: 200 px
   :alt: image of phone
   :align: center

.. _data_point_statistics:

Data point statistics
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can also see an overview of the data collection statistics, by clicking on **Stats** located under the overflow icon as well. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302697/bd98c438-6c0e-11e5-8986-bfe452a9054d.jpg
   :width: 200 px
   :alt: image of phone
   :align: center

.. _monitored_data_points:

Monitored data points
~~~~~~~~~~~~~~~~~~~~~~

A monitored data point is one that contains multiple forms within it. One of these forms is the *Registration form*, which will collect basic identification data about the entity being surveyed. This normally involves collecting the name, location, etc. In essence, the registration form holds attributes that **do not** change over time. All the other forms within a data point are typically used to track change over time.


**Opening a monitored data point**

If you click on a monitored data point, you get access to two tabs: **Forms** and **History**. 

The **Forms tab** shows you the list of all forms under this survey. The first form is the registration form, which you have already filled in when creating the new data point. Therefore, this form is greyed out and you cannot access it to fill in any more data. The following forms in the list are monitoring forms. You can use the same form multiple times to collect data repetitively over time. The version number of each form is displayed, so you can make sure you have the latest form downloaded to your device. Furthermore, the date of the last submission is shown for each form, so it is easy to keep track of the history of data collection for that data point.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302704/c6febcee-6c0e-11e5-9f06-ede4b341b5eb.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *The Forms tab*

The **History tab** contains all the form responses for the given data point. From this tab you can resume an ongoing (not finalized) form, or review an already submitted one. The first form in the list is always the registration form. This gives you direct access to information about that data point. The following submitted forms — which are all monitoring forms — are ordered by submission date, with the most recent submission at the top. By clicking on any submitted form you can see the collected answers. The icons indicate the upload status of the form. For more details check `**Saving and reviewing a form** <http://flow.readthedocs.org/en/latest/docs/flowapp2.2.0/06-Collecting%20data.html#saving-and-reviewing-a-form>`_ . 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302715/d1a859d4-6c0e-11e5-87d7-1fc52a534c85.jpg
   :width: 200 px
   :alt: image of phone
   :align: center

By tapping on the overflow icon in the top right corner you can select either **Languages** or **View map**. **Languages** allow you to switch between the survey languages that are available for that survey. **View map** shows you the location of that one data point.


**Synchronising data points**

Monitored data points can be synchronised. You can download all data points created under the survey from other devices and add new responses to them. This means that one device can create a new data point, add responses, and once the data is sent to the server, a different device can download the data point and keep adding data to it.

To synchronise all data points collected in a project, click on the overflow icon in the upper right corner of your screen and select Sync. Note that you will need a reliable internet connection to perform this action, as the amount of data that will be downloaded can be substantial.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302908/3515d950-6c10-11e5-9bb6-23db97805c80.jpg
   :width: 200 px
   :alt: image of phone
   :align: center

Synchronisation progress is displayed in a notification. You can draw down the status bar in the device to see the progress. Once the synchronisation is finished, the notification will show the total amount of Data Points synced. 

.. _non-monitored_data_points:

Non-monitored data points
~~~~~~~~~~~~~~~~~~~~~~~~

Non-monitored data points contain only a single form. These data points cannot be synchronised either. Only locally collected data will be available in the device. 


**Opening a non-monitored data point** 

If you click on a non-monitoring data point, you get access to the submitted form, to the History,  where you can see the collected answers. By tapping on the overflow icon in the top right corner you can select either **Languages** or **View map**. **Languages** allow you to switch between survey languages that are defined for that survey. **View map** shows you the location of that one data point.

.. _data_point_status:

Data point status
~~~~~~~~~~~~~~~~~
Each data point in the data point list is shown with an icon. There are three icons:

   1. **Saved** (orange with a disk icon) - this means that a form in the data point was started, but not submitted yet. The user needs to go back to the form, finish it, and submit it.
   2. **Exported** (orange with a connectivity icon) - this means that a form in the data point was submitted and exported to the SD-card, but not synced to the server yet. The device needs to have connectivity before it can sync the data.
   3. **Synced** (green with a checkmark icon) - all submitted forms in the data point have been synced to the FLOW server correctly.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10302916/488ee738-6c10-11e5-9268-d74c4cdebe13.jpg
   :width: 300 px
   :alt: image of phone
   :align: center
   
   *Data point status icons* 

If there are multiple forms inside a data point, the icon used will display the ‘worst case’, meaning that if some of the forms are already synced, but one form is exported but not synced yet, it will display the Exported icon.

You can order the data point list according to the status, by selecting the **Status** option in the **Sort** menu option under to overflow icon.

It is extremely important that you check the synchronisation status before deleting data from the device by making sure that all data has a green icon and therefore has been synced correctly. Otherwise you might lose data.

.. _forms:

Forms
-----

Once you create a new data point: 

    - **for non-monitored data points**, you access the form and its questions directly. 
    - **for monitoring data points**, you see two tabs, Forms and History,  where **Forms tab** is opened by default. The Forms tab shows you the list of all forms under this surveys. The first form is the registration form. You start with selecting the registration form and filling in the data. Every time you open an existing data point, you see the list of forms, with the registration form greyed out because it has already been filled in.The monitoring forms can be selected to collect new information. You can collect data repetitively over time using these forms. 

.. _downloading_forms:

Downloading forms
~~~~~~~~~~~~~~~~~

There are three ways to get a form from the FLOW server onto your phone:

**1. Automatic download (create form assignment)**

Every time the Akvo FLOW app is launched, it checks for newly assigned forms and updates to existing forms. If there are new or updated forms available, these are downloaded automatically. When new or updated forms have been downloaded, the status bar shows a notification. This is the easiest way to get a form to the phone.

When you launch the application for the first time, the phone sends a signal to the web-based FLOW Dashboard to indicate that your device is available for form assignments. On the Dashboard, the project manager can assign a form or set of forms to the device, as described here: Viewing and creating survey assignments (LINK MISSING). Assigned forms are automatically downloaded from the FLOW server when your phone is turned on, provided you have internet or network connectivity.

**2. Manual download from Settings menu**

You can also manually download a form. However, this is not recommended, as it will not automatically download updates of forms.

**To download a specific form:** 

   1. Before you start, you need the ID of the form. On the FLOW dashboard, you can find this if you view the details of the form.
   2. On the FLOW app, open the side menu and click Settings.
   3. From the list, select Download Form.
   4. Enter the Authorization passcode, which is “12345” and click OK.
   5. Enter the Form ID of the form you wish to download and click OK.
   6. The form will be downloaded into your app and appears in the list of Surveys in the side menu. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10303044/2e3dd71c-6c11-11e5-9c3e-427ec756739c.jpg
   :width: 1000 px
   :alt: image of phone
   :align: center

**3. Manual form transfer**

Manual form transfer allows you to generate a file of a FLOW form and put it on the FLOW device using a USB cable. This can be useful in situations with low or no connectivity. On the dashboard, you can let the FLOW system email you a zipped version of the form. This file (please don’t unzip it) is then placed in the ‘akvoflow/inbox’ folder on the device. How to do this is described here: Manual survey transfer (LINK MISSING).

.. _Question_groups_and_questions:

Question groups and Questions
-----------------------------

.. _question_groups: 

Question groups 
~~~~~~~~~~~~~~~~~

Each form contains a series of questions and the questions are organized into smaller sets called question groups. Each group of questions appears in a separate tab on the screen. You can fill in the questions in any order, moving from tab to tab. To switch between tabs, you can either swipe the screen, click in the tab title, or click the ‘next’ button at the bottom of the tab.

.. _questions:

Questions 
~~~~~~~~~~

.. _question_types:

Question Types
``````````````

There are a number of different question types:

   - **Free text** - Plain text question. Text can be letters, numbers and symbols.
   - **Option** - Displays a set of pre-set options to select from. Option questions can be single or multiple answer.
   - **Cascading question** - Displays a set of dropdown boxes. You first need to select an item in the first list. After that, subsequent dropdowns are filled with the relevant items.
   - **Number** - Allows only numbers to be typed into the answer entry field.
   - **Geolocation** - Uses the device’s GPS to automatically fill in latitude, longitude and elevation. Click the Check Geo Location button to start searching for the position.
   - **Photo** and **Video** - Displays the option to take a photo or video as part of the form. Click the Take Photo or Take Video buttons on the device to access the device camera.
   - **Date** - Displays a datepicker to select a date in DD-MM-YYYY format.
   - **Barcode** - Displays the option to scan a barcode from the device and record the barcode number in the form. Click the Scan Barcode button to trigger the scan reader app. *Note: Requires an external barcode scanning-app to be installed on the device. Alternatively, a bluetooth barcode reader supporting the HID protocol can be used.*
   - **Geographic shape** - Allows you to define points, lines or areas on the map. The type of shape can be pre-set. For more details on how to create a geographic shape see below.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10429607/1f4cafd8-70fa-11e5-97c1-082a255a7d70.png
   :width: 200 px
   :alt: image of phone
   :align: center

.. _Creating_geographic_shapes: 

Creating geographic shapes 
`````````````````````````

If you want to create a geographic shape there are two ways to do so. One way is to create the shape manually and the other uses the internal GPS of your device.

**Creating a shape manually:**

With this method you can create the shape directly on your screen manually without needing to move around the area to capture it. 

Tap on the map on the location where you want to create your geographic shape. Hold your finger on the location for a few minutes. A pop up window will ask if you want to add a new point at this location. Press ‘OK’ to do so. The point is now added to the map showing the latitude and longitude. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719181/4239df36-5582-11e5-92f1-3bf890da61be.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Adding a point to the map*
   
You can also move the point, if you are not satisfied with its location. In order to move the point you have just created,  place your finger on top of the point. Keep your finger at the point and move your finger towards the desired place. The point will automatically follow your moves. Once you let go of the screen the point will be moved.

In order to add a new point to your line or area you are about to capture, repeat the steps. The points will connect to each other automatically once you add them depending on the selected geographic shape.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719193/5dc8e756-5582-11e5-89be-f47c8adc0941.jpg
   :width: 400 px
   :alt: image of phone
   :align: center
   
   *Creating a new geographic shape* 
   
When you are finished capturing your geoshape, you need to save it. Press on the ‘save’ icon on the top of your screen. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719215/995c346c-5582-11e5-8a49-d5bf2069ef72.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Saving your mapped out shape* 
   
**Creating the shape using the GPS on your device:**

With this method you will be able to capture a geographic shape by using the GPS on your device by walking around or towards the structure you want to map out. 

The steps needed to capture the geographic shape this way do not differ in essence from the above mentioned steps. Position yourself and the device at a corner of the area you want to capture. Click on the ‘add point’ icon on the bottom of your screen. This will start the capturing process. Once clicked on this icon, the point will be shown on the map with its coordinates. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719232/c2bae51a-5582-11e5-903e-e26f472a2906.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Selected point on the map with its coordinates* 
   
Now walk to the next corner of the area you want to capture. You can turn your screen off in the meantime to preserve your battery. Once you arrive at the next corner of your area, add another point to the map. Repeat this process until you have reached the last point of your area. Now you need to walk back to the first point you have captured. The app automatically forms a shape.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719257/e85ca3ee-5582-11e5-8ea9-9be1fac4c302.jpg
   :width: 400 px
   :alt: image of phone
   :align: center
   
   *Mapping out a geoshape using your GPS*

**Deleting a point**

If you need to delete a point from your created shape, press your finger on the point to select it. Click on the ‘delete point’ icon on the bottom of your screen. A pop up window will appear to confirm your actions. Select ‘OK’ if you are sure you want to delete the point. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719270/05d50042-5583-11e5-8f32-7babc9d6b48d.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Delete point icon*
   
**Deleting an entire geographic shape**

To delete the created geographic share, press the ‘delete shape’ icon at the bottom of your screen. A confirmation question will appear in the pop up window. If you are sure, you want to delete the shape, press ‘OK’.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719283/20c22704-5583-11e5-9cd4-878bd3cc426f.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Delete geographic shape icon*

**Geographic shape properties**

If you want to check the properties of your created geoshape, click on the ‘information’ icon on the bottom of your screen. A window will show you information on the point count, length and the size of the area, which are automatically calculated.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719295/3a390c34-5583-11e5-8b35-925a4d69e7ef.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Properties of your created geographic shape*

.. _Mandatory_questions:

Mandatory questions
```````````````````

Questions marked with an asterisk (*) in the title are mandatory. This means that the form cannot be submitted if any of its mandatory questions has not been answered yet. The Submit tab will display a list with all mandatory questions that are still unanswered. Clicking on an item in that list will take you to the corresponding tab and question. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10429818/9f8509a6-70fb-11e5-962e-9a8995fc8ddf.png
   :width: 200 px
   :alt: image of phone
   :align: center


.. _Dependent_questions:

Dependent questions
```````````````````

Some questions are dependent on the answer from a preceding option question in the same form. The question will either be shown or hidden, depending on the answer given to the previous question during data collection.

.. _Help_text:

Help text
`````````

Forms can be configured to include help text. If help is available for a specific question the help icon is displayed next to the question text. Click this icon to open to display the help text.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10429832/c0383ace-70fb-11e5-8cd5-97ab14e39c9c.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Help icon dispalys a pop-up with the question help text.*

.. _language:

Language
~~~~~~~~

If you’ve created forms with translations on the dashboard and assigned them to your devices, you can access those translations on the device. To display one or more translations for a form, select **Languages** in the form menu. This will display all of the available translations (i.e. the ones you entered on the dashboard) for all the forms on the device.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10429863/f8dcf662-70fb-11e5-8f1b-46c99dd55db9.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *You can tick as many languages as you want.*

Tick one or more of the language boxes. Ticking one language will display just that language for the form. Ticking more than one will display multiple languages in different colours. Question text, question options, and help text will be displayed in all of the translations you’ve selected if they’ve been entered and published from the dashboard.

