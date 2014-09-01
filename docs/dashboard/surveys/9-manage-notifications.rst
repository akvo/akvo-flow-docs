Manage Notifications
--------------------

Notifications are event-based messages about FLOW survey activity sent to you via email. They are set at the survey level, and can be sent to any valid email address, regardless of whether the email address belongs to a registered FLOW user.

Notifications are either tied to certain events (survey approval, survey submission) or run at set intervals (nightly raw data report if new data has been submitted).

**To set up notifcations:**

From the left panel of the Edit Survey screen, click on "+ Manage Notifications". This will bring up a screen where you can enter the details of each notification.

 .. figure:: ../img/2-surveys_managenotifications_button.png
   :width: 200 px
   :alt: image of dashboard
   :align: center 

   The Manage Notifications button.
   
 .. figure:: ../img/2-surveys_managenotifications.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   Enter the notification details: email address, event type, option type and expiration date; and click Add.

Enter the recipient's email address, select an Event type, Option and expiration date. Click Add and you will see the details appear below.

 .. figure:: ../img/2-surveys_managenotifications_result.png
   :width: 600 px
   :alt: image of dashboard
   :align: center 

   The notification details appear below after you click Add.

**Email** - the email address to which the notification should be sent. Does not need to be a registered FLOW user.

**Event**

* Raw data reports (nightly) - generates and sends a raw data report each night if new data are submitted for the survey
* Survey submission - send a notifcation each time a survey is submitted from the field (note: this can product a high volume of emails) 
* Survey approval - send a notification each time a survey is approved

**Option** - choose whether to include a download link in the email, or to send any file as an attachment

**Expires** - choose the end date for notification. After this date the user will no longer receive emails for the selected survey event.

If you want multiple event notifications sent to the same user, you must enter them individually.

To delete a notification, locate it in the list of existing notifications and click Remove. To return to the Edit Survey screen, click Close Notifications.