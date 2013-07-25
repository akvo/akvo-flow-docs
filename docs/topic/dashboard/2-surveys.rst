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
++++++++++++++++++++++++++++ (3rd level header)

Surveys consist of questions organized into question groups, so first create the question groups for your survey, and then add questions to them.

To add or edit a question group:

Click on "+ Insert group here." Group #, New group - please change name” appears in the group title spot. Click Edit Group Name to change the name of the group and click Save. 

To view the questions within a question group:

Click Show Questions next to the question group and all the questions in that group will appear below. You can only have the questions showing for one survey group at a time. Click Hide Questions to hide the questions again, or just click Show Questions for another group.

To delete a question group:

Click Delete next to the question group. You'll be asked to confirm whether you'd like to delete the group. 

Note: You cannot delete a question group that contains one or more survey questions.

To change the position of a question group (move):

You can rearrange the position of question groups after you've created them by clicking the Move button next to a survey group. This will show you a Move Group Here button in each new possible location. Click the Move Group Here button where you'd like the new position to be. The group will move accordingly and all the groups will re-number.

To copy a question group within a survey:

Click the copy button next to the group name. Paste Group Here buttons will appear in all of the available places to paste a copy of the question group. Click the Paste Group Here button where you'd like to position the question group copy, and it will copy to that location along with all the question within it.

Creating and editing survey questions
+++++++++++++++++++++++++++++++++++++ (3rd level header)

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

Manage Translations

About the Edit Survey left panel




