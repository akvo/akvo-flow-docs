Reports
=======

The Reports tab in FLOW gives you several options for viewing and exporting data and and results from your surveys.

Charts
------

The FLOW Chart Builder is a data visualization tool for viewing individual survey results quickly on the dashboard in graphical form. The basis for the charts are individual survey question responses to option questions from FLOW surveys submitted to the dashboard.

 .. figure:: img/5-reports_chartbuilder.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Chart Builder showing a doughnut chart built from a FLOW survey question.

To use chart builder, first select a survey group, survey, and question from the dropdown menus. Next select the chart type. Three chart types are available -- doughnut charts (like a pie chart), vertical bar charts and horizontal bar charts. If you would like for the smallest items to be grouped together for better viewing, tick the box next to "Group smaller items." This is good if you have a lot of different reponses in small amounts, since it groups everything under 5 percent, and then breaks those items out for you on the right.

When you have made your selections, click Build Chart, and the chart will display below. If you'd like to select a different question or another type of chart, just revisit your selections and press Build Chart to generate a new chart.


Exporting data and reports
--------------------------

There are several different options for report formats. The simplest and most verstaile are the raw data report and raw text file. The comprehensive report includes some basic graphical and statistical analysis, and the printable survey form is a blank survey in Excel format, for printing and distribution if needed.

 .. figure:: img/5-reports_exportreports.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The options for reports of FLOW data.

To run any report, first select a survey group and survey from the top dropdown menus and click the appropriate export button. Once you do, the report will begin running and be delivered via your browser's download settings. Each report will be saved by its type and survey ID number.

Raw data report
~~~~~~~~~~~~~~~
The raw data report contains responses submitted for a single survey presented in a spreadsheet (.xlsx).  It can be viewed and edited using Microsoft Excel, OpenOffice or any other spreadsheet application that supports the XLSX format.

The format of the spreadsheet is as follows:  the first few columns contain meta data, that is, information identifying each response (Instance), which enumerator gathered the data (Submitter), when the data was gathered, and how long it took to gather each response (Duration).  Thereafter the actual data is presented, each column representing a single question in the survey.

To download the raw data report, click on the export button.  The report will start be generated in the background and will be delivered by email to the address associated with your Akvo FLOW user.  This happens mostly for cases where there is lots of data in a survey. In some cases though (surveys with less data or a recently generated report), the report may have been recently generated and will be delivered instantly to your browser.

Raw data report generation has the following advanced settings:

 .. figure:: img/5-reports_export-raw-data-advanced-settings.png
   :width: 800 px
   :alt: image of dashboard
   :align: center

**Filter reports by date collected** - it is possible to filter the responses in the generated report by date of collection.  You can select the starting and/or ending dates for the responses you would like to view.

**Generate the report for use in an external system** - In cases where the responses will be imported into another system other than Akvo FLOW, it is possible to select the option (under Advanced Settings) to generate the report in a format that can be used in a system other than Akvo FLOW.  Note that a report generated in this format cannot be reimported to Akvo FLOW.

Exporting data point data
~~~~~~~~~~~~~~~~~~~~~~~~~~
To export data, go to the 'Reports' tab, and select the 'Export reports' subtab. Here, you can select a survey group and survey form, and . If you select a survey group that is also a monitored group, a checkbox 'Export only last collection' will be displayed. When this is enabled, only the latest collected data for that survey will be exported. For example, if you have collected water several meter readings for a single water meter, and this checkbox is selected, only the last one will be exported. (see :doc:`../../tutorials/monitoring` for the whole story on how to use monitoring.)

 .. figure:: img/4-monitoring.png
   :width: 800 px
   :alt: Illustration of monitoring
   :align: center

The exported file will contain the data point identifier and the display name as the first two columns. 

In a real-life situation, you might want to export a report which combines answers from different forms. For example, if you are monotoring water meters, you might want to export a file which has the customer name and address, plus the latest value of the water meter reading. At the moment, this type of exporting is not yet possible, but it will be made available in a future version of FLOW.

In the mean time, you can use an excel technique to match data accross different files, based on the identifier of each data point. This uses the VLOOKUP function, as described `in this article <http://howtovlookupinexcel.com/vlookup-between-two-workbooks>`_  and `this instruction movie <https://www.youtube.com/watch?v=809m6kLTfgI>`_. If you need help in implementing this, please contact us as support@akvoflow.org

Comprehensive report
~~~~~~~~~~~~~~~~~~~~
The comprehensive report exports all raw data along with optional summarized survey data for geographic areas and optional charts to an Excel spreadsheet (.xlsx). Because these reports contain analysis and graphs, they may take a long time and generate a large report, depending on the amount of data collected with the selected survey.

The top sheet of a comprehensive report is a full raw data report, and subsequent sheets contain analysis and graphs, broken down by geographic area if you have made that selection when you exported the report and the survey contains geographic areas. By default, comprehensive reports run with geographic summaries and graphs.

Raw text file
~~~~~~~~~~~~~
The raw text file exports all submitted raw data for a single survey to a tab delimited text file (TSV) that can be opened in any text or spreadsheet editor. 

Printable survey form
~~~~~~~~~~~~~~~~~~~~~
The printable survey form is a blank survey form in Excel format (.xlsx) that can be used to distribute a blank survey form or conduct a paper-based survey if needed.

