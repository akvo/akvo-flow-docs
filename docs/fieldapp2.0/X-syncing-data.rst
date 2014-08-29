Data Sync and Storage
=====================

Data Sync
---------

As mentioned in the previous section, if an internet connection is available, data synchronisation happens automatically. No further steps are required from the user once the form is submitted. However, in practice, not always a reliable connection is available, and forms are first **exported** to the SD card before they can be synced. This will allow users to perform a *Bulk Upload* of data, directly retrieving the data from the SD card.

The following diagram shows the different states a form goes through.

   `Saved -> Submitted -> Exported -> Synced`

As you can see, all the forms are first exported to the SD card before they get the chance to be synced. If you need to perform a data *Bulk Upload*, please refer to the corresponding documentation in the **Dashboard** section.

Data Point status
^^^^^^^^^^^^^^^^^

While browsing the Data Point list, you will see that a status is also associated to each point, effectively displaying the synchronisation status. The status shown here is directly inherited from the Data Point's form statuses, always displaying the *worst-case-scenario*. This allows you to quickly spot which Data Points need attention. To determine this status, the following priorities have been established:

    1. Saved
    2. Exported
    3. Synced

Given these priorities, a Data Point will display the *lowest* status among its forms. For instance, a Data Point containing some *synced* forms, one *exported* form, and one *saved* form, will display a **saved** status. If this *saved* form would not have been present in such Data Point, the status will be set to *exported*.

You can order the Data Point list according to the status criteria, by selecting the *Status* option in the *Order By* menu option.

*Insert ordered list screenshot*

It is extremely important that you check the synchronisation status before deleting data from the device. Otherwise you might lose data.

Data Storage
------------

As described, all collected data will be stored in the external storage of the device. You can access the external storage and check out the data files if you need, though it will be only necessary in case of manual data upload, or manual form download.

*Note: don't be confused by the word "external" here. This directory can better be thought as media/shared storage. It is a filesystem that can hold a relatively large amount of data and that is shared across all applications (does not enforce permissions). Traditionally this is an SD card, but it may also be implemented as built-in storage in a device that is distinct from the protected internal storage and can be mounted as a filesystem on a computer.*

The root directory for all Akvo FLOW app files is called *akvoflow*. You can find this folder while browsing the top-level directory of the external storage.

To interact with the data files, the app exposes two different folders inside *akvoflow*: *inbox* and *data*.

Inbox
^^^^^

**inbox** directory is used to manually store form files in the device, in case an internet connection is not available in the device. How to generate form files is described in the **Dashboard** section. Once you have those files, just place them in this directory and open the app. The corresponding projects and forms should be synced now.

Data
^^^^

**data** directory is the root folder for all collected data. All data files are stored here before they are sent to the server. When a form is said to be *exported*, it means that it corresponding files can be found here. If the automatic data sync is not available (i.e. no internet connection available), the data must be synced in a manual way, with an approach known as **Bulk Upload**. To perform a bulk upload, the *data* directory must be compressed into a zip file, and uploaded through the dashboard interface. A detailed description on how bulk upload works is presented in the **Dashboard** section.

Data deletion
^^^^^^^^^^^^^

If you have been using the phones extensively or for a previous data collection, it is important to clean them up properly for the next data collection. 

This is important because data is not automatically deleted by the app, so the *data* folder increases in size. When the automatic data sync is used, this is not an issue, as the phone knows what data has been uploaded, and only uploads non-uploaded data. However, when bulk upload is used, the *data* folder is always uploaded completely, which means that the cumulative data is being send each time. This becomes a burden and increases the risk of the bulk upload failing.

You need to ensure that all that data has been successfully submitted to the FLOW server. This will safeguard you from running the risk of exceeding the storage limits of your phone’s SD card. If you exceed the limits of your phone’s SD card, you could potentially permanently lose form data and/or images.

Therefore, you need to: 

-	make sure all the data and images are uploaded
-	make sure the data is exported to the SD card
-	make sure the *akvoflow* folder is backed up to the hard drive of a computer
-	empty the *akvoflow* folder
-	empty the DCIM folder (which holds the camera images)
