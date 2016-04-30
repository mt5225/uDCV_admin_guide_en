********************************
Datasource and Mapping
********************************


uDCV can connect and fetch data from external database using JDBC, to setup database connection, configure field mapping and schedule data fetch job. 

DataSource Management
======================

To access Datasource Management module, click **Data Source** button on the left-hand navigation bar in the **Management Console**

Create New Datasource
^^^^^^^^^^^^^^^^^^^^^^

1. Click **+Add data source** button on the upper right corner in **Data Source** management UI
2. Input data source information, as shown below:

.. image:: ./images/datasource.png
   :width: 480px

3. Click **Test Connection** button to test database connection.
4. Click **Save** to save new data source.


Edit Existing Datasource
^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Select user to be edit from datasource list under **Data Source** management UI, and click edit icon on the right hand side.

3. Modify datasource information, as shown below:
   
.. image:: images/ds_2.png
   :width: 480px
   
3. Click **Save** button to save change.


Delete Datasource
^^^^^^^^^^^^^^^^^^^^^^
1. Select datasource to be deleted from datasource list under **Data Source** management UI, and click delete icon on the right hand side.
2. Click **OK** to confirm delete. Click **Cancel** to cancel operation.


Dataset Management
====================
Click **Dataset** tag in **Data Source** management UI to access dataset management functions.

Create New Dataset
^^^^^^^^^^^^^^^^^^^
1. Click **+Add dataset** button on the upper right corner.
2. Input data set information, as shown below:

.. image:: ./images/dataset_1.png
   :width: 480px

3. Click **Preview** button to preview data from dataset.

.. note:: 

   First 20 records are shown in preview mode.


4. Click **Save** to save new dataset.


Edit Existing Dataset
^^^^^^^^^^^^^^^^^^^^^^
1. Click **+Edit dataset** button on the right hand side.
2. Input data set information.
3. Click **Preview** button to preview data from dataset.

.. note:: 
   First 20 records are shown in preview mode.

5. Click **Save** to save change.

Delete Dataset
^^^^^^^^^^^^^^^
1. Select dataset to be deleted from dataset list, and click delete icon on the right hand side.
2. Click **OK** to confirm delete. Click **Cancel** to cancel operation.

Data Mapping
=====================
Click **Data Mapping** tag in **Data Source** management UI to access data mapping functions.

Create New Data Mapping
^^^^^^^^^^^^^^^^^^^^^^^^
1. Click **+Add Category Mapping** button on the upper right corner.
2. Input mapping ans scheduler information, as shown below:

.. image:: ./images/mapping_1.png
   :width: 640px

3. Click **Save** to save new data mapping.

.. note::
   There are 6 required field which must exist and mapped from dataset, namely:
   
   * ID
   * Name
   * Belong to 
   * Site
   * Layout
   * deviceModelNumber


Edit Existing Data Mapping
^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Click **+Edit dataset** button on the right hand side.
2. Input mapping information.
3. Click **Save** to save change.


Delete Data Mapping
^^^^^^^^^^^^^^^^^^^^
1. Select data mapping to be deleted from data mapping list, and click delete icon on the right hand side.
2. Click **OK** to confirm delete. Click **Cancel** to cancel operation.
   

Run Data Mapping Job
^^^^^^^^^^^^^^^^^^^^
Data mapping can be run manually or by scheduler. 

* Run Once
  
  Click **Execute once only** to run data import once.

|

* Run by Scheduler
  
  Click **Start execution** to run data import job by scheduler.

Stop Scheduler
^^^^^^^^^^^^^^^
Click **Stop execution** button under data mapping definition to stop data import scheduler for that particular data mapping.




