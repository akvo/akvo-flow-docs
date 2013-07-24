Surveys
=======

Surveys are the centerpiece of the FLOW application. Create, edit and publish surveys from the Surveys tab. 

Survey structure in FLOW
------------------------

Would like to do some kind of side by side visual here, showing how you build it on the Dashboard, and what it looks like on the device.

**Survey Groups**
Surveys on the dashboard are kept in Survey Groups to help stay organized. Survey groups can be organized by any way you'd like - for example, by country, type, organization or year.

**Question Groups**
Each survey contains a series of questions and the questions are organized into smaller sets as question groups.  Each group of questions appears in a separate tab on the device screen. 

**Question Types**

* Free text - shows the user a text box on the device to fill in the answer, with no specific format. Text can be letters, number, and symbols, and appears in the database exactly as it was typed into the device.
* Option - allows the survey author to create a set of preset options for the device user to select from on the device when answering the question. Option questions can be single or multiple answer (Allow multiple). Survey author can elect to allow 'other' responses, which on the device presents a free text field for entering any other response outside the preset options. Option questions will have frequency analysis performed on them in data analysis
* Number - allows only numbers to be typed into the answer entry field on the device. Optional number settings allow the survey author to allow a sign (negative) to be entered with a number, allow a decimal point, or enter minimum and/or maximum values for the number netered on the device. Number questions will have basic statistical analysis performed on them in data analysis.
* Geolocation - uses the device’s GPS to automatically fill in latitude, longitude and elevation. Click the Check Geo Location button to fill in these questions on the device.
* Photo and Video - presents the option to take a photo or video as part of the survey. Click the Take Photo or Take Video buttons on the device to access the device camera.
* Date - presents a date picker on the device for the device user to select a date in DD-MM-YYYY format.
* Barcode - presents the option to scan a barcode from the device and record the barcode number in the survey by clicking the Scan Barcode button on the device. Requires an external barcode scanning-app to be installed on the device to be used.

**Question Features**

* Tooltips - survey author can enter hint or tip text that's visible through an info icon next to the question on the device.
* Dependent - tick this box on the dashboard to make the current question dependent on the answer from any preceeding option question in the same survey. On the device, the survey will adapt to the answers the user selects while conducting the survey as applicable.
* Mandatory- tick this box on the dashboard to make a question mandatory, which means that on the device the user won't be able to submit the survey unless they have answered all mandatory questions.

Working with survey groups
--------------------------

To create a new survey group:

Click Add New Group in the left panel. A text field will appear below. Type the name of the new survey group in here, and press Save to add it to the list below, or Cancel to discard the change.

To edit the name of a survey group:

Click on the survey group in the left panel. The surveys in that group will display to the right, and the name of the group will appear across the top. Click Edit Name next to the survey group name. A text field with the current name of the survey group will appear in place of the name. Enter the new name for the survey group and click Save to save changes, or Cancel to discard.

To delete a survey group:

Click on the survey group in the left panel. The surveys in that group will display to the right, and the name of the group will appear across the top. Click Delete This Group next to the survey group name, which will ask you to confirm whether you'd like to delete the group.

Note: You cannot delete a survey group that contains one or more surveys.

To copy a survey into another survey group:
Hover your mouse over the name of the survey you'd like to copy, and click the Copy button under the survey details. This will bring up a window where you can enter the new name of the copied version of the survey and select the destination survey group. If you don't make a selection for the destination, the survey will copy into the current group. 


Creating and editing a survey
-----------------------------


Text

Publishing a survey
-------------------

Text

   
Next section
-----------------



Click on the SURVEYS tab from the top menu (this is the default landing page when a user first arrives at the dashboard after loading the page.
Click on a survey group from the left Survey groups list. Surveys contained within that group will load in the main body of the page (this is the Survey Group Overview).
Click on “Create a new survey” in the upper right hand corner of the Survey Group Overview. The Edit survey window will appear in the main body of the page.
Enter the required elements in the left bar. Required elements are: Title, Type. Click Save. User should not be able to click Save unless those two elements are filled in. Clicking ‘Save’ causes the Id number to be filled in with the Survey ID from GAE that was just created.
Click on “+ Insert group here” to create a survey group. Group 1, New group - please change name” appears in the group title spot.
Click on “Edit group name” and “New group - please change name” changes to a text box that should be filled in with the group name. Fill in the group name and click SAVE. The new group name appears in the group title sopt.
Click “Show questions” and “Add new question” appears below the group title. Click “Add new question” and a new question edit box appears, “1 new question - please change name.”
Click Edit in the question edit box and the question box screen expands to show editing options.
Enter question text in the “Question text” text box. 
“Question type” dropdown is default set to “Free text.” Picking another type from the dropdown shows the available parameters for those questions.
Click SAVE QUESTION at the bottom of the question edit box.
Repeat steps 5-11 to add more questions.
Click “Publish” in the left bar to publish the survey and make it available for assigning to devices. Clicking publish displays a pop up window: “Publishing survey: The survey has been published. Please consult the messages tab to see if the publishing has succeeded. This may take a few minutes.” Click OK to dismiss the pop-up.
Click the MESSAGES tab from the top menu to move over to the Messages page to confirm survey publishing. Within a few minutes, an entry in the Messages table should appear with the information for the survey just published (Date, Survey ID, Survey, Type, Message, User [will be blank]).
