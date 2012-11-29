Maps
====

Summary: requirement for FLOW 1.5 is to replicate the current 1.0 functionality in the new user interface, with minor alterations to the point type data model and better user-facing integration of the metrics into map display of survey data.

Requirements
------------
**1.5**
^^^^^^^
	* Map displays in Maps tab on Dashboard so that Dashboard users can view map data from within the Dashboard page, and also displays on a publicly-accessible URL so that organizations can share their map with anyone with access to a web browser
	* Map data must also be exportable to a Google Earth file (.kmz)
	* Map displays all surveyed points where point type = access point (formerly waterpoint), and public institution; map does not display data with point type = household
	* Surveyed point = surveyedLocale or accessPoint, survey must have contained "geo" question type in order for a surveyedLocale to be created
	* Map points are displayed using Akvo-designed icons that denote point type
	* Map displays a moveable legend explaining point icons
	* When clicked by user, each point displays a pop-up window with a photo of the point and selection of survey data as determined by the user-defined metrics
	* Map contains dropdown with list of all countries with data for that Dashboard so that users can easily navigate between countries where they have FLOW data
	* Map data are displayed on Google Map platform
	* Map has a footer that contains name of organization(s) that collected the data, link to akvo.org or "powered by Akvo" (need to ask Thomas about this)
	* Water For People map already has styling and we should carry that through into 1.5 on their public map

Non-requirements 
----------------
ie, things we will not do in this version

**1.5**
^^^^^^^

	* Points are not color coded or otherwise scored or categorized beyond point type
	* No zoom levels on maps
	* No point groupings or data aggregation
	
Details (to come)
-----------------
Mapping platform requirements

Point types - currently waterpoint, sanitation point, public institution, household; should be access point, public institution (ie school, clinic), and household

Next step is to have a sector tag (ie water, sanitation, health, food security etc)

Metrics

Pop-up window mock-up

LAST UPDATE : 29 November 2012 cmo