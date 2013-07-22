Devices
=======

The devices tab is mission central for managing all the devices connected with your FLOW Dashboard. 

The Devices List displays a list of all the devices connected to your dashboard.

The Assignments List displays a list of all the assignments that have been created on your dashboard, and allows to to create new ones.

Manual Survey Transfer allows you to create a file of a FLOW survey you've already published that you can email to yourself or your colleagues to install on devices manually, in situations with low or no connectvity to a wireless or mobile network.

Connecting and viewing a device
-------------------------------

Install app on device (link to Getting Phone Ready)

Open app on device while connected to a wireless or mobile network, which will send a ping to the corresponding dashboard to connect it.

From inside the app, set the User (link to article) and Device ID (link to getting phone ready).

Return to the dashboard and check for the device in the Devices List. 

Elements in the Devices List
IMEI
Phone Number
Device ID
Device Group
Last Contact
Version

Managing device groups
----------------------
Device groups allow you to organize the devices attached to your FLOW Dashboard into smaller groups, so that when you create Assignments you can select a device group instead of having to select the devices individually. Each device attached to your dashboard can belong to only one device group, or you can leave a device unassigned.

To create, modify or delete a device group:

To add a device to a device group:

To add your device to a group, find it in the Devices List and tick the box next to it in the first column in the table. Click “Add to device group” from the upper right of the Device List. From the pop-up window that appears, select “akvo test” from the dropdown and click OK.

To change the device group for a device:

To remove a device from a device group:

To select a device group when creating or editing a survey assignment:


Viewing and creating survey assignments
---------------------------------------

To create a new assignment:

Important: a survey must be published before it's available for assignment to device. If you would like to use device groups in your assignment, you must create those first as well.

Once your survey has been published, navigate to the DEVICES tab and confirm that your device is in the Devices List.

Click the Assignments List section, and you’ll see a list of the existing assignments on this dashboard. Click the Create New Assignment button.

In 01. Assignment details, enter the assignment name, start date and expiration date. The assignment name will be used to display the assignment in the Assignments List once you save it. The start date and expiration date will determine the period of time the survey receives auto-updates on the device when the survey is modified and re-published on the dashboard, but the survey will download to the selected device(s) right away once you save the assignment.

In 02. Select survey, select the survey group where you stored the survey(s) you want to assign. Once you make a selection in the dropdown, you’ll see all the published surveys from that group appear in the text box to the right. 

Select one or more surveys from the list by clicking to highlight and then click “+ add selected surveys” below the box. You can select multiple surveys by holding down the shift key (for consecutive items in the list) or the command key (Mac) or control key (PC) (for non-consecutive items).

You’ll see the survey(s) you selected appear to the right in “Preview Survey selection.” You can select multiple surveys from one survey group, or select surveys from several different survey groups and add them. You'll see everything you've selected so far in Preview Survey selection.

In 03. Select devices, select the device group from the dropdown that contains the devices to which you want to send the assignment. When you make a selection in the dropdown, all the devices from that group will appear in the box to the right. You can also select "all unassigned devices" from the dropdown to see all the devices that haven't been assigned to a group. 

Select one or more devices from the list by clicking to highlight and then click “+ add selected devices” below the box. You’ll see the device(s) you selected appear to the right in Preview Device selection.

In both Preview sections, you can clear the individual selections you've made by clicking the delete icon next to an item, or Clear All with the button below.

Once you have made all your selections, click the Save Assignment button at the bottom to save the assignment, or Cancel to lose all changes, and return to the Assignment List. To edit an existing assignment, find it in the Assignments List and click the Edit icon in the Action column for that assignment.

Saving an assignment will trigger the surveys you selected to download onto the devices you selected. You must open the Field Survey app to trigger the download. 

Back up options:
**If they do not download within a few minutes, from the Field Survey app home screen tap Settings > Download Survey. You will be promoted for the admin passcode (12345) and then for the survey ID for the survey you wish to download. You can find this ID on the Dashboard in the Edit survey page in the left panel for your test survey.**


Manual survey transfer (bootstrap)
----------------------------------

The standard inline markup is quite simple: use

* one asterisk: ``*text*`` (result *text*) for emphasis (italics),
* two asterisks: ``**text**`` (result **text**) for strong emphasis (boldface), and

Another section
------------------
List markup is natural: just place an asterisk at
the start of a paragraph and indent properly.  The same goes for numbered lists;
they can also be autonumbered using a ``#`` sign::

   * This is a bulleted list.
   * It has two items, the second
     item uses two lines.

   1. This is a numbered list.
   2. It has two items too.