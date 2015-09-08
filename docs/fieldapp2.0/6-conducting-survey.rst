
Collecting Data
===============

*Note: If you have used your phone in a previous data collection exercise, it is important to clear all the data off of the phone before you begin the next exercise so that you do not run the risk of exceeding the storage limits of your phone’s SD card and potentially losing data.*


Before filling out a form, you need to select the data point for which the data collection is associated to. Refer to the :ref:`projects_and_datapoints` section to learn how to create new data points.

To provide a new set of answers for a form, just click on its name in the *Forms* tab. Alternatively, you can select a saved form in the *History* tab.

Once the form is opened, you can enter responses to the questions. When you finish entering responses, submit the form and the data is sent to the FLOW dashboard, where it will be stored and analysed.

From within the form's menu, we have access to a few set of settings:

* **Clear:** Clears all the responses collected so far, without sending them to the server. To clear the response to a particular question, long-click the question text and click OK. 
* **Languages:** Allows you to select one or more languages in which you want the form questions to appear, if the form was configured to support multiple languages. 

.. figure:: img/survey-menu.png
   :width: 200 px
   :alt: image of phone
   :align: center

Navigating a form 
-----------------
Before you begin collecting data, you must understand that each form contains a series of questions and the questions are organized into smaller sets as question groups. Each group of questions appears in a separate tab on the screen. You can fill in the questions in any order, moving from tab to tab. To switch between tabs, you can either swipe the screen, or click in the tab title.

Question Types
^^^^^^^^^^^^^^

* **Free text** - Plain text question. Text can be letters, numbers and symbols.
* **Option** - Displays a set of pre-set options to select from. Option questions can be single or multiple answer.
* **Cascading question** - Displays a set of dropdown boxes. The enumerator first needs to select an item in the first list. After that, subsequent dropdowns are filled with the relevant items.
* **Number** - Allows only numbers to be typed into the answer entry field.
* **Geolocation** - Uses the device’s GPS to automatically fill in latitude, longitude and elevation. Click the **Check Geo Location** button to start searching for the position.
* **Photo** and **Video** - Displays the option to take a photo or video as part of the form. Click the **Take Photo** or **Take Video** buttons on the device to access the device camera.
* **Date** - Displays a date picker to select a date in DD-MM-YYYY format.
* **Barcode** - Displays the option to scan a barcode from the device and record the barcode number in the form. Click the **Scan Barcode** button to trigger the scan reader app. *Note: Requires an external barcode scanning-app to be installed on the device.*
* **Geographic shape** - Allows the user to define points, lines or areas on the map. The type of shape is pre-set. For more details on how to create a geographic shape see below. 

.. figure:: img/questions.png
   :width: 200 px
   :alt: image of phone
   :align: center

Creating a geographic shape
^^^^^^^^^^^^^^^^^^^^^^^^^^^
Once you reach a question in your form which holds a geographic shape question, you will have to create the shape using the FLOW app.

**Creating a new geographic shape** 

Click on ‘Capture shape’ underneath the question. The app brings you to a new screen with the map showing your current location.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719098/c95bda06-5581-11e5-9680-9e168026884b.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   Initial geographic shape edit screen
   
The ‘blue dot’ indicates your location on the map. If you press the compass icon, located in the top right corner of the map, you will zoom in to see your position in more detail. For more zooming use the ‘plus’ and ‘minus’ icons on the bottom right of your screen. The ‘globe’ icon in the header enables you to select from different map views, such as street view or satellite view.  

**Select your geographic shape**

Click on the ‘plus’ icon in the header. Select which shape you want to create. You can create a point, line or an area. This selection may be pre-set via the dashboard in the Geographic shape question type Settings. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719135/0dbb2378-5582-11e5-9089-0ba02b2d8747.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   Selecting your geographic shape 


**Creating a geographic shape**

If you want to create a geographic shape there are two ways to do so. One way is to create the shape manually and the other uses the internal GPS of your device.

**Creating a shape manually:**

With this method you can create the shape directly on your screen manually without needing to move around the area to capture it. 

Tap on the map on the location where you want to create your geographic shape. Hold your finger on the location for a few minutes. A pop up window will ask if you want to add a new point at this location. Press ‘OK’ to do so. The point is now added to the map showing the latitude and longitude. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719181/4239df36-5582-11e5-92f1-3bf890da61be.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   Adding a point to the map
   
   
You can also move the point, if you are not satisfied with its location. In order to move the point you have just created,  place your finger on top of the point. Keep your finger at the point and move your finger towards the desired place. The point will automatically follow your moves. Once you let go of the screen the point will be moved.

In order to add a new point to your line or area you are about to capture, repeat the steps. The points will connect to each other automatically once you add them depending on the selected geographic shape.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719193/5dc8e756-5582-11e5-89be-f47c8adc0941.jpg
   :width: 400 px
   :alt: image of phone
   :align: center
   
   Creating a new geographic shape 
   
When you are finished capturing your geoshape, you need to save it. Press on the ‘save’ icon on the top of your screen. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719215/995c346c-5582-11e5-8a49-d5bf2069ef72.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   Saving your mapped out shape 
   
**Creating the shape using the GPS on your device:**

With this method you will be able to capture a geographic shape by using the GPS on your device by walking around or towards the structure you want to map out. 

The steps needed to capture the geographic shape this way do not differ in essence from the above mentioned steps. Position yourself and the device at a corner of the area you want to capture. Click on the ‘add point’ icon on the bottom of your screen. This will start the capturing process. Once clicked on this icon, the point will be shown on the map with its coordinates. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719232/c2bae51a-5582-11e5-903e-e26f472a2906.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   Selected point on the map with its coordinates 
   
Now walk to the next corner of the area you want to capture. You can turn your screen off in the meantime to preserve your battery. Once you arrive at the next corner of your area, add another point to the map. Repeat this process until you have reached the last point of your area. Now you need to walk back to the first point you have captured. The app automatically forms a shape.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719257/e85ca3ee-5582-11e5-8ea9-9be1fac4c302.jpg
   :width: 400 px
   :alt: image of phone
   :align: center
   
   Mapping out a geoshape using your GPS

**Deleting a point**

If you need to delete a point from your created shape, press your finger on the point to select it. Click on the ‘delete point’ icon on the bottom of your screen. A pop up window will appear to confirm your actions. Select ‘OK’ if you are sure you want to delete the point. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719270/05d50042-5583-11e5-8f32-7babc9d6b48d.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   Delete point icon
   
**Deleting an entire geographic shape**

To delete the created geographic share, press the ‘delete shape’ icon at the bottom of your screen. A confirmation question will appear in the pop up window. If you are sure, you want to delete the shape, press ‘OK’.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719283/20c22704-5583-11e5-9cd4-878bd3cc426f.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   Delete geographic shape icon
   
**Geographic shape properties**

If you want to check the properties of your created geoshape, click on the ‘information’ icon on the bottom of your screen. A window will show you information on the point count, length and the size of the area, which are automatically calculated.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/9719295/3a390c34-5583-11e5-8b35-925a4d69e7ef.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   Properties of your created geoshape 
   
Dependent questions
^^^^^^^^^^^^^^^^^^^
Some questions are dependent on the answer from any preceding option question in the same form. The form will be adapted (hiding/showing dependent questions) while conducting the form.

Mandatory questions
^^^^^^^^^^^^^^^^^^^
Questions marked with an asterisk(*) in the title are mandatory. This means that the form cannot be submitted if any of its mandatory questions is not answered yet. The *Submit* tab will display a list with all mandatory questions that are still unanswered.

.. figure:: img/invalid-questions.png
   :width: 200 px
   :alt: image of phone
   :align: center

Help text
^^^^^^^^^
Forms can be configured to include help text. If help is available for a specific question the **help** icon is displayed next to the question text. Click this icon to open the help tool.

.. figure:: img/help.png
   :width: 200 px
   :align: center

   Help icon displays a pop-up with the question help text

Language
^^^^^^^^

If you've created forms with translations on the dashboard and assigned them to your devices, you can access those translations on the device for conducting forms in the field.

To display one or more translations for a form, select *Languages* in the form menu. This will display all of the available translations (i.e. the ones you entered on the dashboard) for all the forms on the device.

.. figure:: img/languages.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
   You can tick as many languages as you want
   
Tick one or more of the language boxes. Ticking one language will display just that language for the form. Ticking more than one will display multiple languages in different colours. Question text, question options, and help text will be displayed in all of the translations you’ve selected if they’ve been entered and published from the dashboard.

After completing all the questions, we are ready to *submit* the form.

Submitting a form
-----------------
When you complete a form, you must submit it for upload to the FLOW server for storage and analysis. Immediate submission is recommended so that data backup is available in case your phone is lost or damaged.

To submit a form, navigate to the **Submit** tab, which is the last tab in the form. If there are unanswered mandatory questions, or invalid answers, the Submit tab lists these questions. The **Submit** button is disabled until all invalid questions are handled.

.. figure:: img/submit.png
   :width: 200 px
   :align: center

   Once all the questions are filled in, you can submit the form


When you click **Submit** at the end of a form, the form is locked to prevent further editing, and uploaded to the FLOW server immediately. If network connectivity is not available, the form is queued in the phone until connectivity is restored. The data will automatically be sent to the server. This connection can be via Wi-Fi or over mobile network. 

As detailed in :ref:`surveys_and_datapoints` section, the form status will be displayed in the *History* tab. A queued form will have a **Exported** status, whereas a fully synced form's status will be **Synced**. Not until all the images attached to a form are sent to the server will the status turn into **Synced**. Users do not have to manually send any form from within the device, for all the transmissions are handled automatically as soon as the internet connection is available.

If you want more in-depth information, you can long-click any submitted form to check its *Transmission Status*. This will display the status of any file transmission within the form.

*Note: It is always better to submit data from the device right away over the network. If users store data on their devices while waiting for an opportunity to import it later, there is always the danger of permanent data loss if the device is damaged or lost.*

*Note: Ensure that the 'date and time' setting on your phone is correct before you submit a form.*

Saving and reviewing a form
---------------------------
Form responses are automatically saved as you answer them. You can leave as many saved forms as you want, and continue filling out other data points meanwhile. To retrieve a party filled form, navigate to the data point's *History* tab, and select the desired *saved* form (i.e. you might have to take the GPS location at a water point, and then walk a distance to interview someone to complete the rest of the form).

Under the *History* tab, you can also review the responses of a submitted form, just selecting the form and opening it in *read-only* mode. No further editing will be available for such a form.

Icons next to each form will depict at what stage of transmission it is in. Refer to the :ref:`projects_and_datapoints` section for more details.
