Data
====

High-Level Requirements 
-----------------------
	* Inspect survey data coming in from the field
	* Import data - survey zip files from phones, spreadsheets of cleaned survey data
	* Manage metrics (attributes)

Inspect Data Requirements 
-------------------------
	* View survey data coming in from the field in reverse chronological order
	
Import Data Requirements 
------------------------

Import survey zip and photo jpeg files from phones
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Import spreadsheets of cleaned survey data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
	
**Making report running more user-friendly**
	* autofill .xls and .xlsx in export Save-as
	* Include message in pop-up dialog not to migrate away from page while report is running
	* Long term - get rid of Java applets

Manage attributes (draft)
-------------------------
Attributes are a tool that allow users to compare data over time and across different surveys. They are a meta-layer that live between survey data and surveyed points (surveyedLocales or accessPoints) so that users can change the phrasing of questions but still track and report on the same data fields. They also serve as the link between survey data and the information that appears in the data slide-out windows on the maps.

Attribute data are meant to be comparable.

Attributes touch Surveys, Data and Maps in 1.5, plus Reports in 1.5.x.

**Requirements**
	* Character limit (with spaces) = 100
	* No combination or compound attributes, ie an attribute is a single thing or aspect of an access point that can be compared across surveys or different visits to the same access point, and cannot convey a combination of different kinds of responses
	* Selectable for OPTION, FREE TEXT, NUMBER and DATE question types.

**Basic Attribute Workflow**

	1. From Attribute Manager in the Data tab, user creates attributes.
	2. From question detail screen in Surveys tab, user selects an attribute for each question they would like to tie to an attribute. Attribute selector appears only for FREE TEXT, NUMBER, OPTION, and DATE question types.
	3. If they would like this attribute and the response to appear in the map data slide-out window, they check "Show on map" next to the attribute dropdown.
	4. The map data slide out window shows a standard set of items (Latitude, Longitude, unique code, submission date, photo), and then all of the attributes for which the user has checked "Show on map."

**Questions**
Editing surveys and attributes after initial selections, need to re-save, remap to access point?

**Mockups**

data_manageattributes.bmml
surveys_createnewquestion_text.bmml
surveys_createnewquestion_option.bmml
surveys_createnewquestion_number.bmml




LAST UPDATE : 21 Dec 2012 cmo
