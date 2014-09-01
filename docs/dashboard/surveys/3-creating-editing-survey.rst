Creating and editing a survey
-----------------------------

Click on the SURVEYS tab from the top menu. This is also the home page when you first arrive at the dashboard.

Click on a survey group from the Survey Groups list on the left. Surveys contained within that group will load in the main body of the page (this is the Survey Group Overview). 

For a new survey, click on “Create a new survey” in the upper right hand corner of the Survey Group Overview. 

 .. figure:: ../img/2-surveys_createnewsurvey_button.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   Create a new survey.

The Edit survey window will appear in the main body of the page. Enter the required elements in the left bar: Title and Type. Click Save, which will causes the Id number to be filled in with the Survey ID number.

 .. figure:: ../img/2-surveys_enternewsurveydetails.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

   After clicking Create New Survey, enter the details for the survey in the left panel. The Title and Type are required. The default Master Language is English. You can also edit these details anytime from this panel.
   
 .. figure:: ../img/2-surveys_versionnumber.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

   After you enter the survey details and click Save, the ID number for the survey will appear in the left panel.

To edit an existing survey, hover over the name of the survey with your mouse cursor and click the Edit button that appears below the survey details.

Working with question groups
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Surveys consist of questions organized into question groups, so first create the question groups for your survey, and then add questions to them.

To add or edit a question group:

Click on "+ Insert group here." Group #, New group - please change name” appears in the group title spot. Click Edit Group Name to change the name of the group and click Save. 

 .. figure:: ../img/2-surveys_insertquestiongroup_button.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Insert a new question group.
   
 .. figure:: ../img/2-surveys_editquestiongroupname.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Edit the question group name and click Save.

**View the questions within a question group:**

Click Show Questions next to the question group and all the questions in that group will appear below. You can only have the questions showing for one survey group at a time. Click Hide Questions to hide the questions again, or just click Show Questions for another group.

 .. figure:: ../img/2-surveys_showquestions.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Show the questions in a question group.

**To delete a question group:**

Click Delete next to the question group. You'll be asked to confirm whether you'd like to delete the group. 

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

Creating and editing survey questions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Editing survey questions
++++++++++++++++++++++++

After creating at least one survey group, click Show Questions next to the survey group. Click Add New Question in the position you want the new question, or click Edit next to an existing question, and you will see the question details screen.

 .. figure:: ../img/2-surveys_editquestionscreen.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The edit survey question screen.

In the question details screen that appears, you can fill out the core parameters of the question: question text and question type, as well as several optional elements: question help tooltip, making the question mandatory or making the question dependent on the answer to a preceding question. 

 .. figure:: ../img/2-surveys_editquestion_qtypes.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Select a question type from the dropdown. The default is free text.
   
Some question types also offer additional parameters to fill out, which change the behaviour of the question on the device. Below, these are explained.

**Free text questions**

 .. figure:: ../img/2-surveys_qtypes_freetext.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

A free text question offers two additional options:

* 'Use as data point name' - When you use the FLOW 2.0 app, each datapoint you create is given a name. The name is determined by questions that have this option set. If multiple questions have this option set, the answers to those questions are combined in a single name, separated by a dash ('-'). In this way, you can give data points names that identify what you have surveyed, so they are easy to find back in the list of datapoints.
* 'Require double entry of answer in device' - This can be used to force the user to type the answer to the question twice, which can be used as data verification. This can be useful for items such as telephone numbers, email addresses, or identification numbers, which are easy to type wrong.

**Option questions**

For option questions, you can enter options in the text box that appears below, entering each option on a seperate line. On the device, the default behaviour for option questions is that the device user can only select one answer. You can allow device users to select multiple responses to a question by ticking the box next to "Allow multiple". You can allow device users to enter a free text Other answer on the device by ticking the box next to "Allow other".

 .. figure:: ../img/2-surveys_editquestion_optiondetails.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

   The additional details you can enter for option questions.

**Number questions**

For number questions, there are a few additional settings you can enable. All of these settings are optional. By default, device users cannot enter a positive or negative sign or decimal point for number question responses. You can choose to allow device users to enter numbers with signs and/or enter numbers with decimal points by ticking the boxes next to "Allow sign" and/or "Allow decimal point".

You can also set minumum and/or maximum values for the numbers that the device user can enter. This will prevent them from being able to submit responses outside the specified range.

 .. figure:: ../img/2-surveys_editquestion_numbersettings.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The additional settings you can enter for number questions.

**Geo questions**

For Geo questions, there are two additional options:

* 'Use as data point location' - In some cases, you might have multiple geolocations in a single survey form. In that case, this setting determines which one will be used as the primary location of the datapoint (where a marker will be shown on the map). If there is only a single geoquestion in the form, that one will be used by default.
* 'Disable manual editing of geo values on device' - Setting this option will stop users manually entering latitude and longitude on the device. In almost all cases, the device should provide the GPS coordinates, and manual entry is unwanted. Only in the rare case where you have an external GPS device is manual entry needed.

 .. figure:: ../img/2-surveys_qtypes_geotext.png
   :width: 400 px
   :alt: image of dashboard
   :align: center 

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


Previewing a survey
+++++++++++++++++++

At any point, you can preview a survey by clicking the preview button on the bottom of the left panel in Edit survey, or from the Survey Overview by hovering over the name of the survey with your mouse cursor and clicking Preview under the survey details.

 .. figure:: ../img/2-surveys_preview_survey.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The Preview button from the survey screen.
   
 .. figure:: ../img/2-surveys_preview_surveygroup.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The Preview button from the survey group screen.

The survey preview shows you the survey as it currently stands. It will show you all of the questions in the survey, but if you begin to fill it out and there are dependent questions, the survey display will adapt to the responses. Any responses filled in the preview screen will be discarded when you close the preview window.

 .. figure:: ../img/2-surveys_preview_pop.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   A survey preview.
