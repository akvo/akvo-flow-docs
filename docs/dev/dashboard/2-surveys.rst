Surveys 
=======

Requirements
------------
	* View survey groups
	* Create new survey group
	* Edit survey group
	* Delete survey group
	* View surveys within each survey group
	* Create new survey
	* Edit survey
	* Save survey changes
	* Publish survey
	* View survey status
	* Create web survey (web authorization)
	* Create survey form (printable survey form)

*Required* and *Optional* denote whether the page element is one that the user must complete in order to move forward.

View, create and edit survey groups
-----------------------------------
	* Survey groups are listed in alpha order in the left bar with up and down arrows to navigate
	* Clicking "Add new group" displays a text entry box below it where the user can type in the new group name. Pressing Save saves the new group and it appears in the list below. Pressing cancel does not save it, and it does not appear in the list below. Pressing either save or cancel dismisses the text entry field.
	* Clicking on a survey group in the left bar brings all the surveys from that group into the main body of the page
	* Given a survey group is selected, it is highlighted in orange in the left menu and the name is displayed in the top bar.
	* Given a survey group is selected, {icon} "Edit name" and {icon} "Delete this group" appear in the top bar
	* Clicking "Edit name" replaces the contents of the top bar with a text entry field containing the current name of the survey group. The user can type the new name of the survey group in the text entry field. Clicking "Save" saves the new name of the group, and its display in the left and top bars changes accordingly in display and list position. Clicking Cancel does not save the change and the name of the group in the left menu and top bar does not change. Clicking either Save or Cancel removes the Edit area from the top bar.
	* Given the survey group contains at least one survey, clicking "Delete this group" brings up delete confirmation window that reads "Can't delete survey group: You cannot delete this survey group because it contains surveys. Please delete the surveys individually first." Clicking OK dismisses the window and the survey group is not deleted.
	* Given the survey group does not contain surveys, clicking "Delete this group" brings up a delete confirmation window that reads "Are you sure you want to delete this survey group?: This cannot be undone." Clicking OK dismisses the window and deletes the survey group and it disappears from the list in the left and top bars. Clicking Cancel dimisses the window and does not delete the survey group and it remains in the left and top bars.

View, create, and edit surveys
------------------------------


Create Question
^^^^^^^^^^^^^^^
**General Requirements**
	* Select question type from list of type options: Free text, Option, Number, Geo, Photo, Video, Date, Barcode *Required*
	* Enter question text *Required*
	* Enter translations (one or more) in available languages for question text *Optional*
	* Add help item *Optional*
	* Designate as a mandatory question (ie required for survey submission) *Optional*
	* Make the question dependent on the answer to a previous option question *Optional*
	* Save question or cancel changes 
	* Reorder questions 
	* Delete questions 
	* Copy question and move to a new location **

**Requirements for Option Questions**
	* Enter response options *Required for type = option*
	* Enter translations for each response to correspond to translations entered for question text *Optional*
	* Allow an 'Other' response to a question *Optional*

**Requirements for Number Questions**
	* Enter number validation rules: Minimum and Maximum values, Allow sign (+ or -), Allow Decimal Point *Optional*

Create web survey
-----------------

Summary: A FLOW survey that can be filled out and submitted from a web interface.

Also known as a web authorization.

**Requirements**
	* From somewhere in the Surveys tab, a user can specify a set of parameters and then generate a URL to the web survey that they can share with respondents to fill out and submit from any web browser
		* Parameters are (from 1.0): name for the authorization, expiration date (after which the URL is no longer accessible), survey group and survey, choice between anonymous or user-specific, max number of uses (submissions from the authorization)
	* Existing web authorizations are displayed in a list or table
	* URL send user to the specififed FLOW survey in a webpage, where:
			* Question groups appear as tabs
			* Field types should be enforced appropriate to question types 
				* FREE TEXT - string
				* NUMBER - numbers only
				* OPTION - show option dropdown, along with Allow Other and Allow Multiple tick boxes
				* GPS - fields to enter latitude, longitude (required), altitude, unique code, dropdown pick from existing codes, view map to select location
				* PHOTO - browse and upload
				* VIDEO - browse and upload
				* DATE - date picker
				* BARCODE - number field to enter barcode number
			* Form adapts to dependent questions
		* Submit screen is the final tab, contains a submit button
		* Submit button enforces mandatory questions
	* User sees confirmation pop up when survey is successfully submitted. Pressing Ok returns them to a blank page inside the authorization URL, with a message that states "Thank you for your submission." And a button "Submit Another" Clicking "Submit Another" takes them to a fresh blank web survey screen if they have not met the max number of uses. If they have met the max number of uses for that authorization, display a pop up that informs them of this.
	* Surveys appear as source = WEB FORM in Data listing (Data tab)


	
LAST UPDATE : 02 January 2013 cmo 