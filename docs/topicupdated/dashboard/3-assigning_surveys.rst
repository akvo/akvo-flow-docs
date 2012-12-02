Assign Surveys to Devices 
==========================

To make survey questionnaires available on the field data collection devices, you must assign the survey to specific devices. Surveys must be approved by a FLOW administrator before they can be assigned. 

To assign a survey to a phone you need to know either the device identifier for the phone, the phone number, or the Media Access Control (MAC) address for the phone.

**To assign a survey to a phone**: 

1. From the Data Managers drop-down menu on the Dashboard, select Admin Wizard.  
 
2.	In the left menu, select Assign Surveys to Devices. 
 
3.	Click Create Assignment.
 
4.	You can now specify the devices to which you want the survey assigned.	
 
5.	In the Survey Group drop-down list, select the survey group for the survey you want to assign.
6.	In the Survey field, select the survey. To select multiple surveys, keep the Ctrl key pressed as you click on each survey name. 
7.	Under Devices, all registered phone devices in the system are listed. To select multiple devices, keep the Ctrl key pressed as you click on each device name. Then click Add Selected.
8.	Under Assignment Details, provide a Trip Name, a Start Date, and an End Date. 
9.	Click Save and Continue.  
10.	The survey will now be available on the selected devices the next time the device is turned on, as long as it has either a Wi-Fi connection or a cell connection with a data plan.

Generate Bootstrap File
-------------------------

If network connectivity is low, FLOW provides an alternative way to upload surveys to devices. You can generate a bootstrap file that includes the surveys you want to assign, and email it to users. The files can then be manually loaded onto the device. 

**To generate a bootstrap file**:

1.	In the Admin Wizard menu, select Generate Bootstrap File. 
 
2.	Select the survey that you want to include in the file. In the Survey Group field, select the Survey Group for the survey. 
3.	The Survey field shows all the surveys that come under the selected group. Select the survey or surveys you want to include, and then click Add Selected.
 
4.	The File Contents section shows the list of surveys you selected to include in the file. Review the list to make sure all the required surveys are included. To add more, repeat steps 2 and 3. To remove any surveys that you accidentally included, click Remove Selected.
 
5.	To notify a particular user when the file becomes available, enter the recipient’s email address in the Notification Email field. 
6.	To generate the file, click Generate. 
 
7.	A message confirms file generation. Click OK.
 

Manage Web-based Surveys
========================

When you want to collect data from institutions or selected groups of people, FLOW enables you to generate Web-based versions of the surveys as an alternative to phone-based surveys. These surveys can be made available online, with distribution access provided to selected users. 

Once authorization details are entered in the system, a link to the Web-based survey is generated and the user can send this link by email to all the people who should be included in the survey. The link opens the survey form where responses can be entered. Submitted survey data is automatically loaded onto the FLOW server and made available on the Dashboard. 

To enable users to send online surveys, you must first provide them the required authorization within Admin Wizard.


Edit Web Authorizations
-------------------------

**To authorize access to web-based surveys**:

1.	In the Admin Wizard menu, select Edit Web Authorizations. 
 
2.	In the Survey Group field, select the Survey Group for the survey. The Survey field shows all the surveys that come under the selected group. Select the survey for which you want to provide authorization, and then click Create New Authorization. 
 
*Note: You can provide authorization only for one survey at a time.*

3.	Provide authentication details:

4.	Enter a name for the Web authorization. For example, Public Access. 

5.	Click within the Expiry Date field to select a date from a calendar. This is the date till which the survey should be active. 
 
6.	The survey can be anonymous, or sent to specific users. To send the survey link to selected users only, select the   button next to the User field. 

7.	Click Find User.
 
8.	The list of users available in the system is displayed. To add a user, click Select next to the user’s name. 
 
9.	To search for a user, enter the user’s name or email address in the fields provided and click Search.  
10. To add a new user, enter the user’s name or email address in the fields provided and click Add User.
 
11. After you select the users, click Close.
12. In the Maximum Uses field, enter the number of times this survey can be accessed. 

*Note: The token field is automatically generated once you save your settings.*

13. Click Save and Continue. A confirmatory message appears with the link to the online survey. 
 
14. Copy the link into an email and send it to the list of people from whom you want responses. 
15. Click OK to exit. 
