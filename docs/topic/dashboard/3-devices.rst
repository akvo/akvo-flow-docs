Devices
=======

The devices tab is mission central for managing all the devices connected with your FLOW Dashboard. 

* The Devices List displays a list of all the devices connected to your dashboard.
* The Assignments List displays all the survey assignments that have been created on your dashboard, and allows you to create new ones.
* Manual Survey Transfer allows you to create a file of a FLOW survey you've already published that you can email to yourself or your colleagues to install on devices manually, in situations with low or no connectvity to a wireless or mobile network.

Connecting and viewing a device on the dashboard
------------------------------------------------

First install the latest version of the Field Survey app on your device (link to Getting Phone Ready). While connected to a wireless or mobile network, open the app on the device, which will send a ping to the corresponding dashboard to connect it.

From inside the app, set a User (link to article) and Device ID (link to getting phone ready).

To confirm that the device has connected successfully, visit the Devices tab on the dashboard and check for the device in the Devices List.

[insert image of devices list about here]

.. figure:: img/3-devices-deviceslist.png
   :width: 600 px
   :alt: image of dashboard
   :align: center

**Elements in the Devices List**

* IMEI - an identifying number unique to each device that helps to identify it in our database
* Phone Number - the device's phone number (mobile network) or MAC address (wifi network)
* Device ID - a name you set on the device to help you identify each device
* Device Group - the device group to which the device belongs; optional
* Last Contact - the last time the device connected with the dashboard
* Version - the version of the Field Survey app the device is running

Managing device groups
----------------------
Device groups allow you to organize the all devices attached to your FLOW Dashboard into smaller groups, so that when you create Assignments you can select a device group instead of having to select the devices individually. Each device attached to your dashboard can belong to only one device group, or you can leave a device unassigned.

**To create, change or delete a device group:**

Click the Manage Device Groups button. It will display a pop-up that gives you three choices: change the name of an existing group, create a new device group, and delete an existing device group. Fill out the form as appropriate and click SAVE to save changes, or Cancel to discard changes.

[insert image of Manage device groups pop up about here]

**To add a device or change the device group:**

Find the device(s) in the Devices List and tick the box next to each device in the first column in the table. Click "Add to device group" in the upper right of the Device List. From the pop-up window that appears, select a device group from the dropdown and click OK to save changes, or Cancel to discard changes. You will see the name of the Device Group you just selected in the device row(s) in the Devices List.

**To remove a device from a device group:**

Find the device(s) in the Devices List and tick the box next to each device in the first column in the table. Click "Remove from device group" in the upper right of the Device List. The pop-up window that appears will ask you to confirm the removal. Click OK to remove the device, Cancel to keep the device in it's current group. You will see the name of the Device Group you just removed disappear from the device row(s) in the Devices List.


Viewing and creating survey assignments
---------------------------------------

All survey assignments are listed in the Assignments List section. You can also create new survey assignments here.

The Assignments List contains the Name, Start Date and End Date for every assignment created on your dashboard. You can edit or delete  assignments using the buttons in the Action column in the far right of the table.

**To create a new assignment:**

Important: a survey must be published before it's available for assignment to a device. If you would like to use device groups in your assignment, you must create those first as well.

Once your survey has been published, navigate to the DEVICES tab and confirm that your device is in the Devices List.

Click the Assignments List section, and you’ll see a list of the existing assignments on this dashboard. Click the Create New Assignment button.

*In 01. Assignment details*, enter the assignment name, start date and expiration date. The assignment name will be used to display the assignment in the Assignments List once you save it. The start date and expiration date will determine the period of time the survey receives auto-updates on the device when the survey is modified and re-published on the dashboard, but the survey will download to the selected device(s) right away once you save the assignment.

*In 02. Select survey*, select the survey group where you stored the survey(s) you want to assign. Once you make a selection in the dropdown, you’ll see all the published surveys from that group appear in the text box to the right. 

Select one or more surveys from the list by clicking to highlight and then click “+ add selected surveys” below the box. You can select multiple surveys by holding down the shift key (for consecutive items in the list) or the command key (Mac) or control key (PC) (for non-consecutive items).

You’ll see the survey(s) you selected appear to the right in “Preview Survey selection.” You can select multiple surveys from one survey group, or select surveys from several different survey groups and add them. You'll see everything you've selected so far in Preview Survey selection.

*In 03. Select devices*, select the device group from the dropdown that contains the devices to which you want to send the assignment. When you make a selection in the dropdown, all the devices from that group will appear in the box to the right. You can also select "all unassigned devices" from the dropdown to see all the devices that haven't been assigned to a group. 

Select one or more devices from the list by clicking to highlight and then click “+ add selected devices” below the box. You’ll see the device(s) you selected appear to the right in Preview Device selection.

In both Preview sections, you can clear the individual selections you've made by clicking the delete icon next to an item, or Clear All with the button below.

Once you have made all your selections, click the Save Assignment button at the bottom to save the assignment, or Cancel to discard all changes, and return to the Assignment List. 

Saving an assignment will trigger the surveys you selected to download onto the devices you selected. You must open the Field Survey app to trigger the download. 

**To edit an existing assignment:**

Find it in the Assignments List and click the Edit icon in the Action column for that assignment.

Back up options: (should figure out where to put these)
If they do not download within a few minutes, from the Field Survey app home screen tap Settings > Download Survey. You will be promoted for the admin passcode (12345) and then for the survey ID for the survey you wish to download. You can find this ID on the Dashboard in the Edit survey page in the left panel for your test survey.


Manual survey transfer
----------------------

Manual Survey Transfer (formerly known as bootstrap) allows you to generate a file of a FLOW survey you've already published that you can email to yourself or your colleagues to install on devices manually, in situations with low or no connectvity to a wireless or mobile network.

**To create a survey file:**

*In 01. Select survey*, select the survey group where you stored the survey for which you want to create a file. Once you make a selection in the dropdown, you’ll see all the published surveys from that group appear in the text box to the right. 

Select a survey from the list by clicking to highlight and then click “+ add selected surveys” below the box. You’ll see the survey you selected appear to the right in “Preview Survey selection.”

*In 02. Notification details*, enter the email address to which you'd like to send the survey file. You can enter just one email address. 

Once you are finished, click the Send File button. You'll see a confirmation pop-up. Check your email for an email from "FLOW" with the subject line "FLOW bootstrap file." The email will contain a link to download the bootstrap file. Click the link to download the file to your computer.

**To transfer the file on to to your device:**

Link to app section on this


