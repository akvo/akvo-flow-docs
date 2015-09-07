Creating and editing a survey
-----------------------------

Creating a new survey
~~~~~~~~~~~~~~~~~~~~~~

First, make sure you are in the right folder in which you want to create the survey. Then, click the 'Create new survey' button in the upper right corner.

 .. figure:: ../img/2-new_survey.png
   :width: 200 px
   :alt: image of dashboard
   :align: center 

   Create a new survey.

This creates a new survey, which will be shown in the folder. If you have any subfolders, it will be shown below these.

 .. figure:: ../img/2-new_survey_2.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   The newly created survey, with the 'edit' icon indicated.

To start editing the survey, click the 'edit' icon. This will display the survey edit screen, as shown below. 


 .. figure:: ../img/2-edit_survey_screen.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   The survey edit screen. The red numbers indicate the various functions

A lot is happening here, so we have numbered the areas of interest. Let's go over them one by one:

1. Indicates the number of forms in the survey. A new survey has zero forms.
2. Indicates if this is a monitoring survey or not (more on that below).
3. Indicates if this survey has been published or not (more on that below).
4. The title of the survey. A short title to describe the survey. On the device, this will be shown as the title of the survey as well.
5. The description of the survey. This is an optional description of the survey. It is only used in the dashboard.
6. The privacy type of the survey. There are two possibilities: 'public' and 'private'. This setting determines if the data will be visible on the public map or not.
7. Language: the master language of the survey. In addition to this, any number of translations can be added later. The default master language is English.
8. Advanced settings. Here, you can turn a survey into a monitoring survey (more on that below).
9. Button to add a form to the survey.

After changing the various settings, click 'Save'.

Adding a form
~~~~~~~~~~~~~~

The next step is to add a form to the survey. Most surveys will only have a single form. At the bottom of the survey edit screen, click the 'Add new form' button.

 .. figure:: ../img/2-add_new_form_button.png
   :width: 200 px
   :alt: image of dashboard
   :align: center 

   Adding a new form.

At the bottom of the survey edit screen, a form screen will be shown. 

 .. figure:: ../img/2-new_form_edit.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   The form edit screen

A lot is happening here, so we have numbered the areas of interest. Let's go over them one by one:

1. The version of the form. Each time a form is changed and republished, it's version is updated.
2. The id of the form. This can be used to manually download the form to a device.
3. The current total number of questions in the form.
4. The title of the form. This is the title that is also visible on the device
5. The description of the form. This is only used in the dashboard.
6. Manage Translations. Here, you can add mutliple translations to a form, in any language
7. Manage Notificiations. Here, you can setup automatic distribution of data collected using this form.
8. Insert group. This inserts a new question group, which is the first step in creating the questions of the form.


Start by providing a descriptive title to the form and saving it by clicking the 'Save' button at the top. The next step is defining the questions.

After you save the form, a form screen shows two more buttons:

 .. figure:: ../img/2-surveys_after_save.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

1. The Preview button shows a preview of the entire form
2. The Delete button deletes the form. This cannot be undone. You can only delete a form if it hasn't been used for data collection yet. If you still want to delete it, you will first need to delete the data collected with this form.
3. The further settings of the form are now hidden. Clicking the 'Show' button will show the title and description fields, and the translation and notification buttons.

Advanced - Working with multiple forms
~~~~~~~~~~~~~~~~~~~~~~~~~~~
A regular survey will only contain a single form. However, you can add additional forms to a survey, which capture different aspects about the subject of the survey. For example, if you survey water pumps, you could have a 'registration form' that captures the basic information for a water point, a 'water quality form', that captures water quality information about that point, and a 'functionality update form' that periodically captures the functionality. More on how multiple forms can be used for monitoring is available here: :doc:`./7-monitoring-features`. Here, we simply explain how to add multiple forms.

To add multiple forms to a survey, you first need to enable monitoring on the survey. First go to the survey basics, and select 'Show advanced settings'.

 .. figure:: ../img/2-show_advanced.png
   :width: 200 px
   :alt: image of dashboard
   :align: center 

Next, you can check the checkbox 'Enable monitoring features'. When this has been enabled, you can create multiple forms. In addition, you need to select the form which will be used to create new data points. Other forms will just be able to update existing data points. Please refer to :doc:`./7-monitoring-features` for further details.


 .. figure:: ../img/2-survey_enable_monitor.png
   :width: 200 px
   :alt: image of dashboard
   :align: center 

   Enabling monitoring on a survey.

 .. figure:: ../img/2-extra_form.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   You can now add additional forms to the survey.

Working with question groups
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

A form consist of questions organized into question groups, and it is usually a good practice to first create the question groups for your survey, and then add questions to them.

**To add or edit a question group:**

Click on "+ Insert group here." Group #, New group - please change name” appears as the group title. Click Edit Group Name to change the name of the group and click Save. 

 .. figure:: ../img/2-surveys_insert_group_here.png
   :width: 200 px
   :alt: image of dashboard
   :align: center 

   Insert a new question group.
   
 .. figure:: ../img/2-surveys_editquestiongroupname.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   Edit the question group name and click Save.

**View the questions within a question group:**

Click 'Show Questions' next to the question group and all the questions in that group will appear below. You can only have the questions showing for one survey group at a time. Click Hide Questions to hide the questions again, or just click Show Questions for another group.

 .. figure:: ../img/2-surveys_showquestions.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Show the questions in a question group.

**To delete a question group:**

Click 'Delete' next to the question group. You'll be asked to confirm whether you'd like to delete the group. 

Note: You cannot delete a question group that contains one or more survey questions.

**To change the position of a question group (move):**

You can rearrange the position of question groups after you've created them by clicking the Move button next to a survey group. This will show you a Move Group Here button in each new possible location. Click the Move Group Here button where you'd like the new position to be. The group will move to the spot you selected and all the groups will re-number.

 .. figure:: ../img/2-surveys_movequestiongroup_button.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Click the Move button next to the question group name.
   
 .. figure:: ../img/2-surveys_movequestiongroup.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Select the new position for the question group by clicking the button in the appropriate location.
   
 .. figure:: ../img/2-surveys_movequestiongroup_result.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The question group will move to the new position and the groups will re-number.

**To copy a question group within a survey:**

Click the copy button next to the group name. Paste Group Here buttons will appear in all of the available places to paste a copy of the question group. Click the Paste Group Here button where you'd like to position the question group copy, and it will copy and paste to that location. At the moment, the questions inside the question group are not copied automatically.

 .. figure:: ../img/2-surveys_copyquestiongroup_button.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Click the Copy button next to the question group name.
   
 .. figure:: ../img/2-surveys_copyquestiongroup.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Select the position for the copy of the question group by clicking the button in the appropriate location.
   
 .. figure:: ../img/2-surveys_copyquestiongroup_result.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The question group will be copied and pasted to the selected position and the groups will re-number.
   
The difference between moving and copying a question group is that for a *move*, the question group just changes position in the survey, whereas for a *copy*, the group remains in its current location and a copy is pasted in the new selected location.

**To repeat a question group when collecting data in the field:**

By clicking 'Repeat this group' you will allow the enumerator when collecting data to repeat this group of questions as many times as needed. This will make it possible to ask the same set of question multiple times without needing to predefine then manually in the surveys. For example, if you want it ask the same questions to each member of a household, you will add the questions to one question group and click on the repeat option. 

In the app, once you reach the question group with enabled repetitions, a new button '+ Repeat' automatically appears. By clicking in this button you will get a new set of questions from that question group. Once you are done collecting the data for this set of questions, click on 'Next' to proceed to the following question group. 

In a raw data report, the repeated question group and the collected answers will appear as a grid. Each repetition is placed in a new row and the questions are headers in the columns.   

There are some limitations to repeated question groups: 
   - You will not be able to create a data point name from a question within a repeated question group.
   - The dependecy rule is limited as well. You can make a question the in the repeated group dependent on each other or on a question from another group. However, you cannot make a question dependent on a question from the repeated question group. 

Creating and editing survey questions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Creating a new question
++++++++++++++++++++++++

After creating at least one survey group, click Show Questions next to the survey group. Click Add New Question in the position you want the new question, or click Edit next to an existing question, and you will see the question details screen.

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/8957358/454d32c0-35fe-11e5-8925-af0272e727ab.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The edit survey question screen.

In the question details screen that appears, you can fill out the core parameters of the question: question text and question type, as well as several optional elements: question help tooltip, making the question mandatory or making the question dependent on the answer to a preceding question. 

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/8957430/b3484990-35fe-11e5-8d6b-f876d7e238de.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Select a question type from the dropdown. The default is free text.
   


Question types and their settings
+++++++++++++++++++++++++++++++++

These are the question types available in the FLOW system:

* **Free text** - shows the user a text box on the device to fill in the answer, with no specific format. Text can be letters, numbers and symbols, and appears in the data views and reports exactly as it was typed into the device.
* **Option** - create a set of preset options for the device user to select from on the device when answering the question. Option questions can be single or multiple answer. The survey author can elect to allow 'other' responses, which on the device presents a free text field for entering any other response outside the preset options. Option questions will have frequency analysis performed on them in data analysis. 
* **Cascade** - a cascade question uses a user-defined hieararchy of options in order to display multiple dropdowns on the device. Determining a location is a good example: in a first dropdown question you choose the region, and then in the next dropdown, you can choose from the districts in that region, and so on. The user selects a pre-created cascade from the 'Choose cascade resource' dropdown menu. 
* **Number** - allows only numbers to be typed into the answer entry field on the device. Number questions will have basic statistical analysis performed on them in data analysis.
* **Geolocation** - uses the device’s GPS to automatically fill in latitude, longitude and elevation. Click the Check Geo Location button to fill in these questions on the device. 
* **Photo and Video** - presents the option to take a photo or video as part of the survey. Click the Take Photo or Take Video buttons on the device to access the device camera.
* **Date** - presents a date picker on the device for the device user to select a date in DD-MM-YYYY format.
* **Barcode** - presents the option to scan a barcode from the device and record the barcode number in the survey by clicking the Scan Barcode button on the device. Requires an external barcode scanning-app to be installed on the device.
* **Geographic feature** - allows the user to define points, lines or areas on a map. This can for example be used to capture geographic features of interest such a group of water taps, walking paths, farmer plots, or protected woodland areas. 

Some question types also offer additional parameters to fill out, which change the behaviour of the question on the device. Below, these are explained.

**Free text question settings**

A free text question offers two additional settings: 

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/8957554/7ce9cd3c-35ff-11e5-9f24-726d2a0da6c1.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

* 'Use as data point name' - When you use the FLOW 2.0 app, each datapoint you create is given a name. The name is determined by questions that have this option set. If multiple questions have this option set, the answers to those questions are combined in a single name, separated by a dash ('-'). In this way, you can give data points names that identify what you have surveyed, so they are easy to find back in the list of datapoints.
* 'Require double entry of answer in device' - This can be used to force the user to type the answer to the question twice, which can be used as data verification. This can be useful for items such as telephone numbers, email addresses, or identification numbers, which are easy to type wrong.

**Option question settings**

For option questions, you can enter options in the text box that appears below, entering each option on a seperate line. 

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/8957611/dff47c24-35ff-11e5-8c96-56b53321884c.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

An option question offers three additional settings:
* On the device, the default behaviour for option questions is that the device user can only select one answer. You can allow device users to select multiple responses to a question by ticking the box next to "Allow multiple". 

* You can allow device users to enter a free text Other answer on the device by ticking the box next to "Allow other".

* 'Use as data point name' - When you use the FLOW 2.0 app, each datapoint you create is given a name. The name is determined by questions that have this option set. If multiple questions have this option set, the answers to those questions are combined in a single name, separated by a dash ('-'). In this way, you can give data points names that identify what you have surveyed, so they are easy to find back in the list of datapoints.

**Cascade question settings**

For cascade questions, there is one additional setting you can enable. 

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/9085248/5d0da002-3b7b-11e5-899c-910021643bcf.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

* 'Use as data point name' - When you use the FLOW 2.0 app, each datapoint you create is given a name. The name is determined by questions that have this option set. If multiple questions have this option set, the answers to those questions are combined in a single name, separated by a dash ('-'). In this way, you can give data points names that identify what you have surveyed, so they are easy to find back in the list of datapoints.

**Number question settings**

For number questions, there are a few additional settings you can enable. All of these settings are optional. 

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/8957824/64db2248-3601-11e5-9b58-4ab8409a5915.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

* 'Use as data point name' - When you use the FLOW 2.0 app, each datapoint you create is given a name. The name is determined by questions that have this option set. If multiple questions have this option set, the answers to those questions are combined in a single name, separated by a dash ('-'). In this way, you can give data points names that identify what you have surveyed, so they are easy to find back in the list of datapoints.
* By default, device users cannot enter a positive or negative sign or decimal point for number question responses. You can choose to allow device users to enter numbers with signs and/or enter numbers with decimal points by ticking the boxes next to "Allow sign" and/or "Allow decimal point".
* Require double entry of answer in device’ - This can be used to force the user to type the answer to the question twice, which can be used as data verification. This can be useful for items such as telephone numbers, email addresses, or identification numbers, which are easy to type wrong.
* You can also set minumum and/or maximum values for the numbers that the device user can enter. This will prevent them from being able to submit responses outside the specified range.

**Geolocation question settings**

For geolocation questions, there are two additional options, which are optional:

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/8957899/ce7e612e-3601-11e5-9ee3-b2d1a807377b.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

* 'Use as data point location' - In some cases, you might have multiple geolocations in a single survey form. In that case, this setting determines which one will be used as the primary location of the datapoint (where a marker will be shown on the map). If there is only a single geoquestion in the form, that one will be used by default.
* 'Disable manual editing of geo values on device' - Setting this option will stop users manually entering latitude and longitude on the device. In almost all cases, the device should provide the GPS coordinates, and manual entry is unwanted. Only in the rare case where you have an external GPS device is manual entry needed.

**Barcode questions settings** 

For barcode questions there is one more additional setting:  

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/8957937/27345a1c-3602-11e5-94fa-f63f44b4610a.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

* ‘Enable multiple barcode scan’ - In some cases, you might want to scan multiple barcodes at one. This setting enables you to scan as many barcodes as you need within one question. 

**Geographic shape question settings** 

These settings are available for the geographic shape questions

 .. figure:: https://cloud.githubusercontent.com/assets/12456965/8957984/70be8a0e-3602-11e5-8c98-13adcc433083.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 
   
* For a geographic feature question there is the option to restrict the choice of feature types available to the enumerator. If nothing is selected, the enumerator can choose between points, lines, and areas when she creates a new feature. If you already know that the enumerator will only need to create areas, for example, it makes sense to hide the other options, to avoid confusion.
* ‘Disable manual editing of geo values on device’ - Setting this option will stop users manually entering latitude and longitude on the device. In almost all cases, the device should provide the GPS coordinates, and manual entry is unwanted. Only in the rare case where you have an external GPS device is manual entry needed.

Using tooltips
++++++++++++++

In the optional Question help tooltip text field, you can enter text that might help the device user complete this question. This will display to the device user as a small info icon that they can tap to see the tooltip.

Using dependent questions
+++++++++++++++++++++++++

You can build FLOW surveys that are adaptive to the answers provided by the respondent, so that the questions that appear on the device screen while the survey is being conducted will change according to the answers to previous questions. These are dependent questions.

Dependent questions operate on option questions that preceed the dependent question. 

To set a dependency, tick the box next to "Dependent" in the question detail screen. This will display a dropdown list that contains all the option questions that preceed the current question. Select the question upon which you want the current question to be dependent. The possible responses to that question will appear below. Tick the box next to the response, and the current question will only appear on the device if that response is selected. You can also select more than one response.

 .. figure:: ../img/2-surveys_editquestion_settingdependency.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

   Setting the dependent question.
   
 .. figure:: ../img/2-surveys_editquestion_settingdependencyresponse.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

   Setting the dependent question response.

When you are finished, click Save Question at the bottom of the question details screen, which will return you to the list of questions for that group and you can continue building or editing the survey. 


Previewing a form
+++++++++++++++++++

At any point, you can preview a form by clicking the preview button i
The form preview shows you a preview of the entire form. At first, it will show you all of the questions in the survey. As you start to fill out the form, it will adapt according to any dependent questions you might have defined. Any responses filled in the preview screen will be discarded when you close the preview window.

 .. figure:: ../img/2-preview_button.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   Clicking the preview button will show the form as a preview in a popup screen.

 .. figure:: ../img/2-preview.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

   A survey preview.
