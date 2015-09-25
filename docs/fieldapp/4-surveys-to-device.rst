Getting FLOW surveys onto the device
=====================================

Before you start using the Field Survey application, you must:

•	Connect the phone to a Wi-Fi network or mobile data connection.
•	Set the Access Point Name (APN) 
•	Calibrate GPS 

Connect to a Wi-Fi Network

In order for the phone to update surveys, receive new surveys or transmit submitted surveys, the phone must have a cellular plan with data or must be connected to Wi-Fi. A Wi-Fi internet connection is the easiest way to connect to the FLOW server for data exchange.
 In situations where an internet or data connection is unavailable, see to Handling Network Connectivity Issues for off-line alternatives.

To connect the phone to a Wi-Fi network:

1.	On the home screen of the phone, press Settings. 
2.	Under Wireless and Network, the default setting for Wi-Fi is OFF. Tap on OFF to change it to ON. 
3.	Select Wi-Fi. A list of available Wi-Fi networks displays. 
4.	Choose the network you have access to and provide the password, if prompted. 
5.	Select Connect. When connected to Wi-Fi, you can see this  icon at the top of the screen.

If you have successfully `installed the Field Survey App on the phone <https://flow.readthedocs.org/en/latest/docs/fieldapp/2-preparing-device.html#installing-field-survey-app>`_  and have internet or network connectivity, your phone is ready to receive surveys. 

*Note: It is important to know that you should close and open the App, the connection will be refreshed. If FLOW doesn’t work, you can try refresh the connection. This often helps.*

**There are four ways to get a survey from the FLOW server onto your phone:**

•  `Automatic download <https://flow.readthedocs.org/en/latest/docs/fieldapp/4-surveys-to-device.html#automatic-download-create-survey-assignment>`_ :  Assign a survey to your phone from the FLOW Dashboard, which will then be downloaded by the phone automatically. Survey assignment is done by the project manager. 
•	`Reload all Survey <https://flow.readthedocs.org/en/latest/docs/fieldapp/4-surveys-to-device.html#reload-all-surveys>`_ : By reloading all surveys, the application tries to connect to the server and update with the latest version. If this doesn’t work, you need to download survey from settings menu. 
•	`Download survey from settings menu <https://flow.readthedocs.org/en/latest/docs/fieldapp/4-surveys-to-device.html#manual-download-from-settings-menu>`_ : Download a specific survey from the Settings menu on the Field Survey App installed on your phone.
•	`Manual transfer (bootstrap) <https://flow.readthedocs.org/en/latest/docs/fieldapp/4-surveys-to-device.html#id1>`_ : Generate a bootstrap file containing the survey from the FLOW Dashboard and manually transfer the survey to your phone using a USB cable. This is also done by the project manager. 


Automatic download (create survey assignment)
---------------------------------------------
Every time the Field Survey App is launched, it checks for newly assigned surveys and updates to existing surveys. If there are new or updated surveys available, these are downloaded automatically. When new or updated surveys have been downloaded, the status bar shows a notification. This is the easiest way to get a survey to the phone.

When you launch the application, the phone sends a signal to the web-based FLOW Dashboard to indicate that your device is available for survey assignments. On the Dashboard, the project manager can assign a survey or set of surveys to the device. Assigned surveys are automatically downloaded from the FLOW server when your phone is turned on, provided you have internet or network connectivity. Shortcuts to these surveys appear on the Field Survey home screen.  

.. figure:: img/4-1automatic_download_installed_surveys_updated.png
   :width: 200 px
   :alt: image of phone
   :align: center

You can see the full notification by drawing down the status bar (put your finger on the top of the screen and slide downwards. Slide upwards again to close the notification screen).

.. figure:: img/4-1automatic_download_installed_surveys_updated2.png
   :width: 200 px
   :alt: image of phone
   :align: center


Reload all surveys
------------------
If you have tried the automatic download, but they survey doesn’t show up, you can try to **reload all surveys**: 

1. Close and open the application. By doing this, the application tries to connect to the server and update with the latest version. 
2.	If this doesn’t work, you need to manual download survey from settings menu. 


Manual download from settings menu
----------------------------------
**To download a specific survey:**

Before you start, you need the ID of the survey. On the dashboard, you can find this if you view the details of the survey. 
1.   On the Field Survey home screen, click **Settings**. 

.. figure:: img/4-3field_survey_app_settings.png
   :width: 200 px
   :alt: image of phone
   :align: center

2.   From the list, select **Download Survey**.

.. figure:: img/4-3download_survey.png
   :width: 200 px
   :alt: image of phone
   :align: center

3.   Enter the Authorization passcode **12345** and click **OK**.

.. figure:: img/4-3authorization_passcode.png
   :width: 200 px
   :alt: image of phone
   :align: center

4.   Enter the Survey ID of the survey you wish to download and click **OK**.

.. figure:: img/4-3enter_survey_ID.png
   :width: 200 px
   :alt: image of phone
   :align: center

5.   The shortcut to the downloaded survey appears on the Field Survey home screen. Use the shortcut to launch the survey.

*Note: If the downloaded survey does not appear immediately on the home screen, close the application and reopen it.*



Manual transfer (bootstrap)
---------------------------
Manual Survey Transfer (formerly known as bootstrap) allows you to generate a file of a FLOW survey you've already published that you can email to yourself or your colleagues to install on devices manually, in situations with low or no connectvity to a wireless or mobile network. How to do this is described in the `Manual survey transfer section <https://flow.readthedocs.org/en/latest/docs/fieldapp/4-surveys-to-device.html#id1>`_ of the Akvo FLOW dashboard documentation.
