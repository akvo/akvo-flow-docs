Surveys 
=======

Requirements
------------
	* View survey groups
	* Create survey group
	* Edit survey group
	* View surveys
	* Create and edit survey
	* Publish survey
	* View survey status
	* Create web survey (web authorization)
	* Create survey form (printable survey form)

*Required* and *Optional* denote whether the page element is one that the user must complete.

Create and edit surveys
-----------------------

Create Question Group
^^^^^^^^^^^^^^^^^^^^^

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

Create web survey (web authorization)
-------------------------------------

Summary: A FLOW survey that can be filled out and submitted from a web interface.

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


	
LAST UPDATE : 19 December 2012 cmo