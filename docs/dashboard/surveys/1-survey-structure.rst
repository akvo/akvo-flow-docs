Survey structure in FLOW
------------------------

**Survey Groups**

Surveys on the dashboard are kept in Survey Groups to help stay organized. Survey groups can be organized by any way you'd like - for example, by country, type, organization or year. They are displayed in alphabetical order in the left panel of the Surveys tab.

A regular survey group does just that: organise surveys together in a group. However, in a dashboard in which monitoring features are enabled, a survey group can be turned into a 'monitoring group', which means that the surveys in that group are now connected, and are about the same data point type. More information on how this works is available here: :doc:`../tutorials/monitoring`

**Question Groups**

Each survey contains a series of questions and the questions are organized into smaller sets as question groups.  Each group of questions appears in a separate tab on the device screen. 

**Question Types**

* **Free text** - shows the user a text box on the device to fill in the answer, with no specific format. Text can be letters, numbers and symbols, and appears in the data views and reports exactly as it was typed into the device.
* **Option** - create a set of preset options for the device user to select from on the device when answering the question. Option questions can be single or multiple answer. The survey author can elect to allow 'other' responses, which on the device presents a free text field for entering any other response outside the preset options. Option questions will have frequency analysis performed on them in data analysis. The setting 'Require double entry of answer in device' can be used to force the user to type the answer twice, which can be used as data verification. This can be useful for items such as telephone numbers, email addresses, or identification numbers, which are easy to type wrong.
* **Number** - allows only numbers to be typed into the answer entry field on the device. Optional number settings allow the survey author to allow a sign to be entered with a number, allow a decimal point, or enter minimum and/or maximum values to validate the number entered on the device. Number questions will have basic statistical analysis performed on them in data analysis.
* **Geolocation** - uses the device’s GPS to automatically fill in latitude, longitude and elevation. Click the Check Geo Location button to fill in these questions on the device. If you select 'Disable manual editing of geo values on device', the user cannot type in latitude and longitude values directly, the device has to provide them. Usually this is better for data quality. The checkbox 'Use as datapoint location' is only relevant if you use a survey which captures multiple locations in a single survey. In that case, this setting wil determine which location will be used as the primary location of the datapoint. If only a single geoquestion is present in a survey, that will be used by default.
* **Photo and Video** - presents the option to take a photo or video as part of the survey. Click the Take Photo or Take Video buttons on the device to access the device camera.
* **Date** - presents a date picker on the device for the device user to select a date in DD-MM-YYYY format.
* **Barcode** - presents the option to scan a barcode from the device and record the barcode number in the survey by clicking the Scan Barcode button on the device. Requires an external barcode scanning-app to be installed on the device.

**Question Features**

* **Tooltips** - survey author can enter hint or tip text that's visible through an info icon next to the question on the device.
* **Dependent** - tick this box on the dashboard to make the current question dependent on the answer from any preceeding option question in the same survey. On the device, the survey will adapt to the answers the user selects while conducting the survey as applicable. You can select multiple answers on which to make the question dependant by highlighting them in the list that appears when you select the preceding dependent question.
* **Mandatory**- tick this box on the dashboard to make a question mandatory, which means that on the device the user won't be able to submit the survey unless they have answered it and all other mandatory questions.
