Preparing your device for FLOW 
==============================

Before you install the Field Survey App
---------------------------------------
Before you install the Field Survey App on your phone, ensure that your phone is in proper working condition. Place the SD card, the SIM card, and the battery in the phone and make sure you can send and receive calls and data. Once this is done, ensure that your phone is configured to do the following:

• 	Configure Gmail on the phone
•	Configure Android settings for software download
•	Set up Wi-Fi
•	Set Access Point Name (APN)
•	Calibrate GPS

How to do this is described below.

Configure Gmail on phone
-------------------------------------
A free Gmail account is necessary to install the Field Survey App, and to receive updates.  

It is best to use a dedicated email address for communication with the phone. If you intend to use multiple phones with the Field Survey App, use the same email address for all the phones, so that you can send software updates to all the phones simultaneously. If you are an enumerator, it is likely that the phone is already set up correctly.

**To configure Gmail on the phone:**

1. From the home screen of the phone, go to the **settings** menu by clicking on the menu button on the phone (usually at the bottom left, but can be in different places depending on the model of the phone). 

.. figure:: img/2-1settings_from_homescrean.png
   :width: 200 px
   :alt: image of phone
   :align: center

2. Under **Accounts & Sync** or **Accounts**, press **Add account**.

.. figure:: img/2-1add_gmail_account.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
3. From the list of options, select **Google**. 

.. figure:: img/2-1add_gmail_select_google.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
4. You are prompted to specify whether you want to create a new Google account or use an existing one. If you already have a Gmail account that can be dedicated for communication with the FLOW server, choose **Use an existing one**. Otherwise, choose **New**.  

.. figure:: img/2-1add_gmail_add_new_google_account.png
   :width: 200 px
   :alt: image of phone
   :align: center

5. Follow onscreen prompts to create your Google account.

The new account will now be visible under **Applications > Email**.


Configure Android settings for software download
-------------------------------------
Your phone must be configured to allow download and installation of third-party software, so that you can download and install the Field Survey App, and other recommended software.

To enable software download:

1.	Under **Settings**, select **Security**.

.. figure:: img/2-1settings_security.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
2.	Enable **Unknown Sources**. If you cannot find the **Unknown Sources** option under **Security**, check under **Applications**.

IMAGE


Set up Wi-Fi
-------------------------------------
In order for the phone to update surveys, receive new surveys or transmit submitted surveys, the phone must have a cellular plan with data or must be connected to Wi-Fi. A Wi-Fi internet connection is the easiest way to connect to the FLOW server for data exchange.

**To connect the phone to a Wi-Fi network:**

1.	On the home screen of the phone, press **Settings**. 

2.	Under **Wireless and Network**, the default setting for Wi-Fi is **OFF**. Tap on **OFF** to change it to **ON**. 

3.	Select **Wi-Fi**. A list of available Wi-Fi networks displays. 

4.	Choose the network you have access to and provide the password, if prompted. 

5.	Select **Connect**. When connected to Wi-Fi, you can see this IMAGE img/wifi_icon.png icon at the top of the screen.

*Note: In situations where an internet or data connection is unavailable you need to setup data collection via Mobile networks (H, 3G, E, G). To do this you need to enable ‘Use packet data’ or ‘Data roaming’.*


Set Access Point Name (APN)
-------------------------------------
Depending on your situation, this section may not be necessary. If your data plan is already working for your phone, you can skip this.

Local Internet service providers use APN settings to activate data plans using SIM cards on phones that were purchased abroad. Every service provider has different APN settings and they change these settings periodically for security reasons. When you purchase the SIM cards, ask the Internet Service Provider to give you the correct APN settings for the SIM Card.

To set the Access Point name:

1.	On the home screen, press **Settings**. 

2.	From the options, choose **More…** and then select **Mobile Networks**.

.. figure:: img/2-1set_APN_select_more_from_settings.png
   :width: 200 px
   :alt: image of phone
   :align: center

3.	Select **Access Point Name**.

.. figure:: img/2-1set_access_point_name.png
   :width: 200 px
   :alt: image of phone
   :align: center

4.	Press the **Menu** button and select **New APN**.

.. figure:: img/2-1select_new_APN.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
5.	Fill in the required APN settings for your SIM card. You can get the correct APN settings for the SIM Card from your Internet Service Provider.

.. figure:: img/2-1select_new_APN.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
6.	Press the **Home** key when you are done.   
   
   
   
Setting data and time on the phone
-------------------------------------











Installing Field Survey App
---------------------------
Create shortcut
Install recommended applications
Adjust camera resolution

---

old content from Essential Phone Set up:

Before you can start using the Field Survey app, these steps need to be taken:

1. **General phone setup** - Put the SD card, the SIM card, and the battery in the phone, and make sure everything works.
	
2. **Set up Wifi** - Connect the phone to a wifi network. Click on the menu button and select "Settings". Select "Wireless & Networks". Select "Wifi settings". A list of available wifi networks will be displayed. Choose the one you have access to and provide the password. Check if you have an internet connection.
	
A wifi internet connection is the easiest way to get the Field Survey app and updates on the phone, to download surveys, and to upload data. However, if internet is unavailable, all of these actions can also be performed off-line. Please consult the :ref:`Troubleshooting section <troubleshooting>` for these off-line alternatives.

3. There are a few other (free) applications that can be useful when using FLOW. In particular, these are the FileManager app (XXX-LINK-XXX), the GPS Status app (XXX-LINK-XXX), and the ZXing Barcode Scanner app ((XXX-LINK-XXX)). The FileManager app can be used as a backup option to install and update the Field Survey app, when the email method does not work (XXX-reference-XXX). The GPS Status app enables you to monitor and check the GPS function of the phone (XXX-reference-XXX). The ZXing Barcode Scanner app is needed if barcodes are part of your survey (XXX-reference-XXX).

.. note::
	If you have used your phone in a previous data collection exercise, it is important to clear all the data off of the phone before you begin the next exercise so that you do not run the risk of exceeding the storage limits of your phone's SD card and potentially losing data. If you use your phone for ongoing data collection, it is important to clear the phone of data at regular intervals. Refer to `Clearing phones of data <http://flow.readthedocs.org/en/latest/docs/topic/fieldapp/2-preparing-phone/2-9-clearing-phone-data.html>`_ for instructions for this process.
	

old content from 1.0 doc

Installing the Field Survey app
=================================

There are different ways to install the Field Survey app on the phone. In future versions of Akvo FLOW, it will become possible to download the application from the Android Market (now called Google Play), but currently that is not yet possible.

**Android settings** - All of the methods outlined below require a change in the Android settings. The change will allow the installation of applications from other sources then the Android Market. To do this, click on the Menu button and select 'Settings'. Select 'Applications', and enable 'Unknown Sources'. Sometimes, this setting is found under "Security".

.. figure:: img/3-installing-app-1-arrow.gif
   :width: 200 px
   :alt: image of phone
   :align: center

Installation through Gmail
---------------------------
This is the easiest way to get the application on the phone. Don't forget to change the Android settings, see above. These are the steps:

1. Configure email on the phone. You will need to use a gmail account - other email addresses such as hotmail, won't work. It is advisable to use a special email address for this, which is only used to communicate with the phone. If you have multiple phones with the Field Survey app, the same email address can be used for all. In that way, you can send updates to the software to all phones in one go.

2. Get the right Field Survey app (APK file) for your Dashboard. Be careful to get the right one: the Field Survey app and the Dashboard are connected, so you can't simply use any Field Survey APK file for this. You can download the latest version of the APK for your organisation from the Dashboard you have access to, at (XXX-location in Dashboard-XXX) 
 
3. Send an email with the Field Survey app (APK file) as an attachement to the gmail email address that is configured on the phone.

4. Open the email app on the phone. If you don't have the email app icon on your home screen, you can `create a shortcut <create_shortcut>`. 

.. figure:: img/3-installing-app-2-arrow.gif
   :width: 200 px
   :alt: image of phone
   :align: center

Locate the mail.

.. figure:: img/3-installing-app-3-arrow.gif
   :width: 200 px
   :alt: image of phone
   :align: center

5. Open the mail. The APK file will be shown as an attachment. The way attachements are shown will depend on the email app.

.. figure:: img/3-installing-app-4-arrow.gif
   :width: 200 px
   :alt: image of phone
   :align: center


5. Click "Install". Sometimes you have to click 'Load' first.
	
.. figure:: img/3-installing-app-5.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
.. figure:: img/3-installing-app-6.png
   :width: 200 px
   :alt: image of phone
   :align: center
   
The Field Survey app is now installed on the phone. You can now create a shortcut to the Field Survey app on the home screen. This will make starting up the app during field work easier. To do this, just long press on an empty home screen space and choose "Shortcuts" from the menu. Select "Applications", and select the Field Survey app. This will place a shortcut to the Field Survey app on your home screen.


Installation through the FileManager
--------------------------------------





Installation through the Terminal
-----------------------------------


----

Contents:

.. toctree::
   :maxdepth: 3
   
   
   2-preparing-device/2-1-before-install-app
   2-preparing-device/2-2-install-app
   2-preparing-device/2-3-setting-up-users
   2-preparing-device/2-4-launching-app
   2-preparing-device/2-5-updating-app
   2-preparing-device/2-6-uninstall-app
   2-preparing-device/2-7-clearing-device-data
   
