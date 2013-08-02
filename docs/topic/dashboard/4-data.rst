Data
====

The Data tab is where you can view, edit, import and clean data from FLOW surveys. 


`Navigating the map <http://flow.readthedocs.org/en/latest/docs/topic/dashboard/6-maps#navigating-the-map.html>`_ 


Inspect Data
------------

The Inspect Data table is a live feed of all the data submitted from devices connected to your FLOW dashboard. Its default view contains all data, with the most recent records at the top. You can page through the data using the Next and Previous buttons at the bottom of the table, or filter based on a collected of parameters.

For each data record submitted, the table contains:

* ID - unique number assigned to the data record by the FLOW database when it's submitted from the device
* survey - the survey group and survey that was used to collect the data record
* submitter - the user name set on the device from 'Manage Users', to identify which device user submitted the data record
* device ID - the device ID set in the device preferences, to help identify the device
* collected - the date and time the data record was submitted from the device
* action - options to edit and delete (for Admin level users)

Filtering data
~~~~~~~~~~~~~~

There are a collection of paramaters above the data table that allow you to filter what data records you see. You can filter on one or more parameters by making your selection(s) and then clicking the Find button. The records in the table will filter accordingly. To return to the full listing, clear all the filters and press Find again.

Editing data
~~~~~~~~~~~~

To edit a data record, locate it in the data table and click Edit in the Action column. The Edit Answers window will appear.

[Insert screenshot of Edit answers window about here]

The Edit Answers window contains a list of the questions and their responses for that record. Fields that are editable have blue text. When you click on blue text you can edit the answer to that question, clicking Save when you are done, or Cancel to discard the changes. Free text and number questions will display a text field, option questions will display a dropdown menu with the available reponse options, and date question will display a date picker. 

[insert screen shot of in-progress edit of text field and option question]

For photo questions, clicking "Open photo" will open the photo in a new browser window, where you can view or save the photo.

Note: Once you change an answer, this permanently changes the answer in the database and you cannot go back or undo the changes.

Deleting data
~~~~~~~~~~~~~

You can delete individual data records by locating a record in the data table and clicking Delete in the Action column.

Note: Only Admin level users have the Delete option available. This action permanently deletes the data record from the FLOW database and cannot be undown.


Bulk upload data
----------------

The bulk uploader gives you a way to upload data and photo files taken off the device in bulk when data have been collected offline due to limited connectivity circumstances in the field. The tool imports the selected device data zip and image jpeg files and stores them in the database with the appropriate survey.

To load files into the bulk uploader, either drag and drop them into the box on the dashboard, which will start the upload right away, or click "select from computer" and select the files to upload.

For instructions on how to pull files off devices and prepare them for upload when the data were collected offline, see the [link to Field Survey app section on this].

Note: Navigating away from the page while the upload is in progress, either by navigating elsewhere on the dashboard or closing the browser window will interrupt and cancel the upload in progress.

After you drop or select the files, you will see a progress bar below informing you of the upload contents and status. When the upload is complete, you'll see a confirmation message. After the initial upload, it will take some time before the data are available on the rest of the dashboard for viewing and reporting. Check the Messages tab to confirm when the data are available.


Data cleaning
-------------

After data have come in from the field they sometimes require cleaning to correct things like errors or mis-spellings. In data cleaning, you can export a raw data report into Excel, clean the data as necessary, and then re-import the spreadsheet. This action will permanently overwrite the existing data in the database with the cleaned data you import. The spreadsheet you import must by in .xls or .xlsx format.

To export the raw data report, first select a survey group and survey from the dropdown menus. Click Raw Data Report under Export raw data report and the report will download through your browser. Perform a "Save As" on the report to preserve the original download, and clean the data in the new version.

When you are ready to re-import the cleaned data spreadsheet, select the survey group and survey from the dropdown menus. Click Choose File under Import cleaned survey data, and select the spreadsheet from the location where you saved it on your computer. You'll see the file name appear next to Choose File after you've selected it. Click Import Clean Data and the spreadsheet will begin to import.

A progress bar will appear below informing you of the content and status of the import. When the import is complete, you'll see a confirmation message. After the initial import, it will take some time before the data are available on the rest of the dashboard for viewing and reporting. Check the Messages tab to confirm when the data are available.






