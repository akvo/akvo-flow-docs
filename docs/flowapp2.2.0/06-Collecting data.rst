Collecting data
==============

*Note: If you have used your phone in a previous data collection exercise, it is important to clear all the data off of the phone before you begin the next exercise. This is vital to avoid the risk of exceeding the storage limits of your phone’s SD card resulting in potential data loss. Before you delete data, make sure all the data has been synced — i.e. they should have a green icon.*

.. _filling_out_a_new_form:

Filling out a new form
---------------------

You can either fill in information for a new form or finish filling out data in a form you already worked on and is saved on your device. 

**Filling out a new form**

If you want to fill in a new form, click on the ‘+’ icon. This will create a new data point. If you have a non-monitoring survey, you will access the list of questions directly. If you are collecting information for a monitoring survey, after clicking on the ‘+’ icon, you need to select the registration form from the list of available forms. The registration form is the only form in the list which you can select. Only after submitting the registration form, you can collect data using the monitoring forms.

**Filling out a saved form**

If you want to continue filling out a form you previously worked on, you first need to select the data point for which the earlier data collection was done. If this is a non-monitored data point, you will get direct access to the questions and you can continue with your data collection. If this is a monitored data point, after selecting the point, go to the History tab and select your saved form. Now you can finish your data collection work. 

**Form menu**

When collecting data, you have access to a number of settings via the overflow icon in the top right corner:

   - **Languages**: Allows you to select one or more languages in which you want the form questions to appear, if the form was configured to support multiple languages.
   - **Clear**: Clears all the responses collected so far, without sending them to the server. To clear the response to a particular question, long-click the question text and click OK.
   

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10303065/63ced44e-6c11-11e5-81fc-714e6fd599f5.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *Form menu*

.. _submitting_a_form:

Submitting a form
-----------------

When you complete a form, you must submit it for upload to the FLOW server for storage and analysis. Immediate submission is recommended so that data backup is available in case your phone is lost or damaged.

To submit a form, go to the **Submit** tab, which is the last tab in the form. If there are unanswered mandatory questions, or invalid answers, the Submit tab lists these questions. Clicking on a question in this list will take you to the right tab, so you can provide the missing information. The Submit button is disabled until all invalid questions are handled.

Once all the questions are filled in, you can submit the form. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10303070/6d8bf444-6c11-11e5-8b2d-fafa85ea12a5.jpg
   :width: 400 px
   :alt: image of phone
   :align: center

When you click **Submit** at the end of a form and then **OK**, the form is locked to prevent further editing, and uploaded to the FLOW server immediately. If network connectivity is not available, the form is queued in the phone until connectivity is restored. The data will automatically be sent to the server when the device is connected to the internet, either via Wi-Fi or over a mobile network.

.. _Saving_a_form:

Saving a form
---------------------------

Form responses are automatically saved as you answer them. You can leave as many forms in a saved state as you want, and continue filling out other data points meanwhile (i.e. you might have to take the GPS location at a water point, and then walk a distance to interview someone to complete the rest of the form). In order to find back the right data point, it is important that the name of the data point is meaningful. In the Dashboard, questions can be selected that make up that data point name.

There are two ways to retrieve a partly filled form depending on the type of survey you are working with:

**For a non-monitoring survey** simply select the data point from your data point list. This will open the saved form and you can immediately continue with your data collection work. 

**For a monitoring survey** select the data point from the list, navigate to the data point’s **History tab**, and select the desired saved form.

.. _Reviewing_a_submitted_form:

Reviewing a submitted form
---------------------------

As you collect your data, you might want to review the forms you have already submitted. There are two ways of accessing your already submitted answers depending of the type of survey: 

**For a non-monitoring survey** simply select the data point you want to review. This will open the submitted form and you can see the answers directly.

**For a monitoring survey** you first need to select a data point from your list and navigate to the data point’s History tab. Now select the form you want to review the answers.

For both types of surveys, non-monitoring and monitoring, each submitted form holds its own menu. You can access it from the overflow icon when you are reviewing a form. The menu of a submitted form holds three options: **Languages**, **View map** and **Transmission History**. **Languages** allow you to switch between survey languages that are defined for that survey. **View map** shows you the location of that one data point. **Transmission History** shows you the details of the submission of that particular form, as for example when the submission started and the time it was finished. 

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10664866/2a3a6d20-78c7-11e5-9f96-2d5888b9e74b.jpg
   :width: 200 px
   :alt: image of phone
   :align: center
   
   *The menu of a submitted form.*

.. _form_satus:

Form status
-----------

Each form you have collected data against has a specific status. You can see this status in two places depending on what kind of survey you are working with:

**For a non-monitoring survey**, the data point status is equivalent to the form status and shown in the list of data points. For more details on data point status check `Data point status <http://flow.readthedocs.org/en/latest/docs/flowapp2.2.0/04-Data-collection-structure.html#data-point-status>`_.

**For a monitoring survey**, the form status is shown once you select your data point in the History tab. 

A form response can have the following statuses:

   - **Saved**: This form is not submitted yet, and can be resumed in order to add more answers.
   - **Exported**: This form is submitted and exported in the SD card, but the device has not synchronised it with the dashboard. As soon as an Internet connection is available, it will be sent.
   - **Synced**: This form is submitted and fully synchronised with the dashboard. Not until all the images attached to a form are sent to the server will the status turn into Synced. Users do not have to manually send any form from within the device, for all the transmissions are handled automatically as soon as the internet connection is available.

.. figure:: https://cloud.githubusercontent.com/assets/12456965/10303081/778321fc-6c11-11e5-920d-81c646529300.jpg
   :width: 300 px
   :alt: image of phone
   :align: center
   
   *Form status icons in the History tab.*

*Note: It is always better to submit data from the device right away over the network. If users store data on their devices while waiting for an opportunity to import it later, there is always the danger of permanent data loss if the device is damaged or lost.*

*Note: Ensure that the ‘date and time’ setting on your phone is correct before you submit a form.*
