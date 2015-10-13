Data sync and Storage
=====================

.. _data_sync:

Data sync
--------

If an internet connection is available, either through 3G, 4G or Wi-Fi, data synchronisation happens automatically. No further steps are required from the user once the form is submitted.

If an internet connection is not available, data will be stored on the device for later upload. After a form has been submitted, it is both stored in the internal database of the device, and exported to the SD-card. This makes it possible to directly retrieve the data from the SD-card, and do a *bulk upload* to the dashboard if necessary. If you need to perform a data Bulk Upload, please refer to the corresponding documentation in `The Dashboard - Data - Bulk upload data tab <http://flow.readthedocs.org/en/latest/docs/dashboard/4-data.html#bulk-upload-data-tab>`_. Doing this is a bit technical, and is only recommended in cases of very low bandwidth or no internet connection.

.. _upload_status:

Upload status
-------------

The status of your submission is shown either in the data point list, as the data point icon, or under the History tab, as the form status icon. There are three types of statuses: **saved**, **exported** and **synced**. For more information see `Data point status <http://flow.readthedocs.org/en/latest/docs/flowapp2.2.0/04-Data-collection-structure.html#data-point-status>`_.

.. _data_storage: 

Data storage
-------------

All collected and submitted data is stored on the external SD-card or in the internal storage of the device.

The directory that holds all Akvo FLOW files is called *akvoflow*. You can find this folder while browsing the top-level directory of the external storage.

To interact with the data files, the app has two different folders inside *akvoflow: inbox* and *data*.

.. _inbox:

Inbox
~~~~~

The **inbox** is the directory where a user can manually put a form zip file, in case an internet connection is not available. How to generate form files is described in `The Dashboard - Devices - Manual survey transfer <http://flow.readthedocs.org/en/latest/docs/dashboard/3-devices.html#manual-survey-transfer>`_. Once you have those files, just place them in this directory (without unzipping them)  and open the app. The corresponding projects and forms will be synced now.

.. _data:

Data
~~~~

The **data** directory is the folder where all collected data is stored. All data files are stored here before they are sent to the server. When a form is exported after being submitted, it means that it corresponding files can be found here. If the automatic data sync is not available (i.e. no internet connection available), the data must be synced in a manual way, using **Bulk Upload**. A detailed description on how bulk upload works is presented in `The Dashboard - Data - Bulk upload data tab <http://flow.readthedocs.org/en/latest/docs/dashboard/4-data.html#bulk-upload-data-tab>`_.

.. _data_deletion:

Data deletion
~~~~~~~~~~~~~~

If you have been using the device extensively, for example for a previous data collection, it is probably a good idea to clean them up for the next data collection, in order to reclaim space.

This is important because data is not automatically deleted by the app, so the data folder increases in size. We do this to protect data from accidental deletion. If the data folder becomes too large, the SD-card might run out of space. This can be checked here: `Check SD card status <http://flow.readthedocs.org/en/latest/docs/flowapp2.2.0/01-Before-installing-the-FLOW-app.html#check-sd-card-status>`_.

In addition, a large data folder becomes a problem when bulk data upload is used. During bulk data upload, the whole data folder is uploaded, including all data that might have already been uploaded before. Although the FLOW Dashboard ignores data that has already been uploaded before, uploading a large file which includes old data can be difficult.

Before you delete data, you need to make sure that all data has been successfully submitted to the FLOW server. You can delete the data though the **Delete Collected Data and Images** and **Delete Everything** options under **Settings**. 



