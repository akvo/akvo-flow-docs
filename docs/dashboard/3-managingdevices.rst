Managing data collection devices
================================
The Devices tab is mission central for managing all the devices connected with your FLOW Dashboard. 

* The Devices List displays a list of all the devices connected to your dashboard.
* The Assignments List displays all the survey assignments that have been created on your dashboard, and allows you to create new ones.
* Manual Survey Transfer allows you to create a file of a FLOW survey you've already published that you can email to yourself or your colleagues to install on devices manually, in situations with low or no connectvity to a wireless or mobile network.

Connecting and viewing a device on the dashboard
------------------------------------------------

First install the latest version of the Field Survey app on your device. While connected to a wireless or mobile network, open the app on the device, which will send a ping to the corresponding dashboard to connect it.

From inside the app, set a User and Device ID.

Read more about `Preparing your devices for FLOW <http://flow.readthedocs.org/en/latest/docs/topic/fieldapp/2-preparing-device.html>`_ and `Launching and setting up the Field Survey app <http://flow.readthedocs.org/en/latest/docs/topic/fieldapp/3-launching-app.html>`_.

To confirm that the device has connected successfully, visit the Devices tab on the dashboard and check for the device in the Devices List.

 .. figure:: img/3-devices_deviceslist.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The Devices List.

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

 .. figure:: img/3-devices_managedevices_pop.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Change, create or delete a device group and click Save.

**To add a device or change the device group:**

Find the device(s) in the Devices List and tick the box next to each device in the first column in the table. Click "Add to device group" in the upper right of the Device List. From the pop-up window that appears, select a device group from the dropdown and click OK to save changes, or Cancel to discard changes. You will see the name of the Device Group you just selected in the device row(s) in the Devices List.

 .. figure:: img/3-devices_addtogroup_button.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Tick the box next to a device in the list and then click Add to device group.

 .. figure:: img/3-devices_addtogroup_pop.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Select the device group to which you'd like to add devices and click Save.

**To remove a device from a device group:**

Find the device(s) in the Devices List and tick the box next to each device in the first column in the table. Click "Remove from device group" in the upper right of the Device List. The pop-up window that appears will ask you to confirm the removal. Click OK to remove the device, Cancel to keep the device in it's current group. You will see the name of the Device Group you just removed disappear from the device row(s) in the Devices List.

 .. figure:: img/3-devices_removefromgroup_button.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Tick the box next to a device in the list that you'd like to remove and then click Remove from device group.

