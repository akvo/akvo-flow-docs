Surveys
=======

Surveys are the centerpiece of the FLOW application. Create, edit and publish surveys from the Surveys tab. 

Survey structure in FLOW
------------------------

[Would like to do some kind of side by side visual here, showing how you build it on the Dashboard, and what it looks like on the device.]

**Survey Groups**
Surveys on the dashboard are kept in Survey Groups to help stay organized. Survey groups can be organized by any way you'd like - for example, by country, type, organization or year.

**Question Groups**
Each survey contains a series of questions and the questions are organized into smaller sets as question groups.  Each group of questions appears in a separate tab on the device screen. 

**Question Types**

* Free text - shows the user a text box on the device to fill in the answer, with no specific format. Text can be letters, number, and symbols, and appears in the database exactly as it was typed into the device.
* Option - create a set of preset options for the device user to select from on the device when answering the question. Option questions can be single or multiple answer (Allow multiple). Survey author can elect to allow 'other' responses, which on the device presents a free text field for entering any other response outside the preset options. Option questions will have frequency analysis performed on them in data analysis.
* Number - allows only numbers to be typed into the answer entry field on the device. Optional number settings allow the survey author to allow a sign (negative) to be entered with a number, allow a decimal point, or enter minimum and/or maximum values for the number entered on the device. Number questions will have basic statistical analysis performed on them in data analysis.
* Geolocation - uses the device’s GPS to automatically fill in latitude, longitude and elevation. Click the Check Geo Location button to fill in these questions on the device.
* Photo and Video - presents the option to take a photo or video as part of the survey. Click the Take Photo or Take Video buttons on the device to access the device camera.
* Date - presents a date picker on the device for the device user to select a date in DD-MM-YYYY format.
* Barcode - presents the option to scan a barcode from the device and record the barcode number in the survey by clicking the Scan Barcode button on the device. Requires an external barcode scanning-app to be installed on the device to be used.

**Question Features**

* Tooltips - survey author can enter hint or tip text that's visible through an info icon next to the question on the device.
* Dependent - tick this box on the dashboard to make the current question dependent on the answer from any preceeding option question in the same survey. On the device, the survey will adapt to the answers the user selects while conducting the survey as applicable. You can select multiple answers on which to make the question dependant by highlighting them in the list that appears when you select the preceding question.
* Mandatory- tick this box on the dashboard to make a question mandatory, which means that on the device the user won't be able to submit the survey unless they have answered it and all other mandatory questions.

Working with survey groups
--------------------------

The Survey Overview page for each survey group shows all the surveys in that group. To see the overview page, click on a Survey Group name in the list on the left. Each survey in the overview shows the date the survey was created, date it was last modified, type and master language. Hovering over the survey name with your mouse cursor will show four action options: Edit, Preview, Delete and Copy.

**To create a new survey group:**

Click Add New Group in the left panel. A text field will appear below. Type the name of the new survey group in here, and press Save to add it to the list below, or Cancel to discard the change.

**To edit the name of a survey group:**

Click on the survey group in the left panel. The surveys in that group will display to the right, and the name of the group will appear across the top. Click Edit Name next to the survey group name. A text field with the current name of the survey group will appear in place of the name. Edit the name for the survey group and click Save to save changes, or Cancel to discard the change.

**To delete a survey group:**

Click on the survey group in the left panel. The surveys in that group will display to the right, and the name of the group will appear across the top. Click Delete This Group next to the survey group name, which will ask you to confirm whether you'd like to delete the group.

Note: You cannot delete a survey group that contains one or more surveys.


Creating and editing a survey
-----------------------------

Click on the SURVEYS tab from the top menu. This is also the home page when you first arrive at the dashboard.

Click on a survey group from the Survey Groups list on the left. Surveys contained within that group will load in the main body of the page (this is the Survey Group Overview). 

For a new survey, click on “Create a new survey” in the upper right hand corner of the Survey Group Overview. The Edit survey window will appear in the main body of the page. Enter the required elements in the left bar: Title and Type. Click Save, which will causes the Id number to be filled in with the Survey ID number.

To edit an existing survey, hover over the name of the survey with your mouse cursor and click the Edit button that appears below the survey details.

Working with question groups
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Surveys consist of questions organized into question groups, so first create the question groups for your survey, and then add questions to them.

To add or edit a question group:

Click on "+ Insert group here." Group #, New group - please change name” appears in the group title spot. Click Edit Group Name to change the name of the group and click Save. 

**View the questions within a question group:**

Click Show Questions next to the question group and all the questions in that group will appear below. You can only have the questions showing for one survey group at a time. Click Hide Questions to hide the questions again, or just click Show Questions for another group.

**To delete a question group:**

Click Delete next to the question group. You'll be asked to confirm whether you'd like to delete the group. 

Note: You cannot delete a question group that contains one or more survey questions.

**To change the position of a question group (move):**

You can rearrange the position of question groups after you've created them by clicking the Move button next to a survey group. This will show you a Move Group Here button in each new possible location. Click the Move Group Here button where you'd like the new position to be. The group will move accordingly and all the groups will re-number.

**To copy a question group within a survey:**

Click the copy button next to the group name. Paste Group Here buttons will appear in all of the available places to paste a copy of the question group. Click the Paste Group Here button where you'd like to position the question group copy, and it will copy to that location along with all the question within it.

Creating and editing survey questions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

After creating at least one survey group, click Show Questions next to the survey group. Click Add New Question in the position you want the new question, or click Edit next to an existing question.

In the question details screen that appears, you can fill out the core parameters of the question: question text and question type, as well as several optional elements: question help tooltip, making the question mandatory or making the question dependent on the answer to a preceding question. Some question types also offer additional parameters to fill out.

When you are finished, click Save Question at the bottom of the question details screen, which will return you to the list of questions for that group and you can continue building or editing the survey. 

At any point, you can preview a survey by clicking the preview button on the bottom of the left panel in Edit survey, or from the Survey Overview by hovering over the name of the survey with your mouse cursor and clicking Preview under the survey details.

Publishing a survey
-------------------

When you are ready to make a survey available to a set of devices, you'll need to Publish it. Up until this point, you can use Save to store all your changes. Click Publish at the bottom of the left panel in Edit Survey to publish the survey and make it available for assigning to devices. Clicking publish displays a pop up window: “Publishing survey: The survey has been published. Please consult the messages tab to see if the publishing has succeeded. This may take a few minutes.” Click OK to dismiss the pop-up.

Click the MESSAGES tab from the top menu to move over to the Messages page to confirm survey publishing. Within a few minutes, an entry in the Messages table should appear with the information for the survey just published (Date, Survey ID, Survey, Type, Message, User [will be blank]).

Copying a Survey
----------------

Hover your mouse over the name of the survey you'd like to copy, and click the Copy button under the survey details. This will bring up a window where you can enter the new name of the copied version of the survey and select the destination survey group. If you don't make a selection for the destination, the survey will copy into the current group. 

Deleting a Survey
-----------------

To delete a survey, hover your mouse cursor over the survey name in the Survey Overview and click Delete. You will be asked to confirm whether you want to delete the survey.

Note: You cannot delete a survey that contains one or more questions, or that has had any data collected with it.

Manage Notifications
--------------------

Notifications are event-based messages about FLOW survey activity sent to you via email. They are set at the survey level, and can be sent to any valid email address, regardless of whether the email address belongs to a registered FLOW user.

Notifications are either tied to certain events (survey approval, survey submission) or run at set intervals (nightly raw data report if new data has been submitted).

**To set up notifcations:**

From the left panel of the Edit Survey screen, click on "+ Manage Notifications". This will bring up a screen where you can enter the details of each notification.

[insert screenshot of Notifications screen about here]

Enter the recipient's email address, select an Event type, Option and expiration date. Click Add and you will see the details appear below.

Email address - the email address to which the notification should be sent. Does not need to be a registered FLOW user.
Event - 
Raw data reports (nightly) - generates and sends a raw data report each night if new data are submitted for the survey
Survey submission - send a notifcation each time a survey is submitted from the field (note: this can product a high volume of emails) 
Survey approval - send a notification each time a survey is approved
Option - choose whether to include a download link in the email, or to send any file as an attachment
Expires - choose the end date for notification. After this date the user will no longer receive emails for the selected survey event.

If you want multiple event notifications sent to the same user, you must enter them individually.

To delete a notification, locate it in the list of existing notifications and click Remove. To return to the Edit Survey screen, click Close Notifications.


Manage Translations
-------------------

cmo note: we may want this to be it's own page

FLOW allows users to enter alternate translations for surveys on the dashboard, and then make those available on the Field Survey app. This allows data collectors in the field to conduct surveys in their local language.

Survey translations work in the FLOW dashboard version 1.6.0 and higher, and FLOW field survey app version 1.11.0 and higher. Akvo updates your dashboard automatically, but You need to update your field survey app to the latest version to use translations and other new features. If you don’t update the app, you’ll still be able to enter translations on the dashboard, but you won’t see them when you access the languages list on the field survey app.

To build survey translations into a FLOW survey, you follow the same core workflow, but will use the Master Language and Manage Translations tools in the left panel of the Edit Survey screen.

The elements that will show their translations on the device are the question text, option question answers and tooltips. The translations of the survey title, survey description and question group names aren't available on the device yet.

Every survey will have a master language. This is the language in which you will first create the survey, and the language in which you will view and edit data in reports, charts and maps. The default is English if you don’t make another selection when you are initially building the survey.

There are 181 languages available in the language list, but any language with a non-Roman alphabet or any language that reads anything other than left-to-right is experimental at this point. We are working actively with partners to build greater compatibility for different character sets.

**To create and publish a survey with one or more translations:**

From the SURVEYS tab, select a survey group from the left panel in which you’d like to create a new survey for translation, or chose a survey group with an existing survey to which you’d like to add a translation. Once inside the group, click Create New Survey in the upper right or click Edit under the existing survey.

If it’s a new survey, in the Edit survey panel that appears on the left, enter a title for the survey and select a type (both required). Here is where you set the master language for the survey: if you want to change it to something other than English (the default) do that from the MASTER LANGUAGE dropdown. You should not change the master language after you’ve begun to collect data with the survey, so make sure your selection is correct.

[insert image of left panel with master language and manage translations highlighted about here]

Click Save at the bottom of the left panel. You’ll see a number appear next to ID Number in the left panel after you do this. This is the survey ID.

If you are creating a new survey, you’ll create question groups, and then add questions to them. If not, you’ll simply enter translations for the existing questions.

First complete and save the survey in the master language. When you are satisfied, click the “+ MANAGE TRANSLATIONS” button in the left panel. This will bring up the Survey translation screen for the survey. Here you can add one or more translations to your survey. Along the top you’ll see the default (master) language, the existing translations (if you’ve created any) and an ADD NEW TRANSLATION dropdown. Below, you’ll see the master survey details on the left, and the details for the translation on the right, with text boxes to enter a translation for each item.

[Insert image of Survey Translation screen about here]

Select a language from the ADD NEW TRANSLATION dropdown along the top of the Survey translation section. Two buttons, ADD and CANCEL, will appear to the right of the dropdown when you do this. Click ADD to proceed with entering a translation for that language. “Survey details in [selected language]” will appear as the heading for the right-hand translation section.

Enter translations for each survey question, tooltip, and question option (if it’s an option question). The translations for survey title, survey description and question group name will not be visible on the device in this version, but they will be in future versions, so you can enter them as well.

To save as you are working, click SAVE AND CONTINUE at the bottom of the window. To save and return to the master survey screen, click SAVE AND CLOSE. You can always revisit the translation screen by clicking the “+ MANAGE TRANSLATIONS” button from the left panel of the Edit survey section. You can also add multiple translations to a single survey by selecting another language from the Add New Translation dropdown and clicking ADD.

When you have completed the translation(s) of your survey, from the bottom left panel, click Publish. This will display a pop-up window confirming your survey has been published, and instructing to you visit the MESSAGES tab to confirm when this is complete. If you have any unsaved changes, you will first see a warning to Save first.

Once the survey has been published, create a new survey assignment specifying the new survey and all devices that should receive it.

**Navigate and display translations on device:**

Once you have loaded the survey with translations onto a device, you can select any of the available languages and conduct surveys in them. To display one or more translations for a survey, first tap the survey icon for your survey from the field survey app home screen. This will open the survey.

From here, tap your device’s menu button, which will prompt a set of options to slide up from the bottom of the screen. Select Languages. This will display all of the available translations (ie, the ones you entered on the dashboard) for all the surveys on the device.

[Insert image of selecting Languages after pressing Menu on device about here]

[Insert image of languages list on device about here]

Tick one or more of the language boxes. Ticking just one language will display just that language for the survey. Ticking more than one will display multiple languages in different colors. The question text, question options, and tooltips will display in all of the translations you’ve selected if they’ve been entered and published from the dashboard.

Complete the survey and click the Submit button at the end. The notifications bar across the top of the phone screen will tell you when the survey data has been successfully submitted. You can also check this from the Survey Status icon from the app home screen, from Review Submitted Surveys.






