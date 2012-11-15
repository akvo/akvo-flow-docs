Data
====

LAST UPDATE : 15-Nov-2012 cmo

High-Level Requirements 
-----------------------
	* View survey data coming in from the field
	* Import survey zip files from phones
	* Export raw data reports
	* Re-import cleaned survey data
	* Manage metrics

Inspect Data Requirements 
-------------------------
	* View survey data coming in from the field
	
Import Survey Data Requirements 
-------------------------------
	* Import survey zip and photo jpeg files from phones
	
Spreadsheet Export Requirements (Raw Data Report)
-------------------------------------------------
	* Export raw data reports for surveys
	
**Streamed Exporting** [feature update] - https://github.com/akvo/akvo-flow/issues/73

FLOW users were finding a failure point when they tried to export data reports with large numbers of cells (rows x columns). The data export applets were consuming large amounts of Java heap when the spreadsheet was assembled in memory, and when they exceed the heap space capacity, the reports were failing. We will soon reach a point when a survey has more data than can be exported on a 32-bit machine.

We needed a report exporter that reduces memory consumption so that users can run reports big and small.

Approach: Using the streaming version (SXSSF instead of XSSF) of the OpenXML access API should lower memory requirements.

**Requirements**
	* Dashboard users can export a spreadsheet (raw data report) with up to 1,650,000 cells (eg 3000 rows x 550 columns)
	* Example data set of sufficient size can be found in Issue 84 https://github.com/akvo/akvo-flow/issues/84
	
**Making report running more user-friendly**
	* autofill .xls and .xlsx in export Save-as
	* Include message in pop-up dialog not to migrate away from page while report is running
	* Long term - get rid of Java applets


Spreadsheet Import Requirements 
-------------------------------
	* Re-import spreadsheets of cleaned survey data
