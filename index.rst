.. |plugin| image:: ./img/logo.png
   :width: 2.5em
.. |plugin2| image:: ./img/logo2.png
   :width: 2.5em

.. _introduction:

============
Introduction
============

Dear user, welcome to **Gisquick** documentation!
Gisquick (http://gisquick.org) is an open source geospatial data platform for publishing geospatial data in terms of rapid
sharing `QGIS <http://qgis.org>`__. Explore more to see how easy yet powerful is working in Gisquick.

There are few topics you might be interested in. Firstly, if you are about to **publish** your **QGIS**
**project online**, see chapter **1** to **4**. Please note that there are two alternative ways of publishing
so the choice must be made which one to follow (chapter **2** or **3**). Together with every released project,
web map service (**WMS**) is created and can be subsequently modified.

If you wonder **what does the output look like** or **which features are involved**, check chapter **5**.
Browse chapter **6** for **metadata of example datasets** which were used for documentation. If you plan to
**operate Gisquick publication server** on your own hardware, see chapter **7**.

List of chapters follows below.


1. **Creating account**
-----------------------
It is necessary to create an account.

2. **Traditional publishing**
-----------------------------
Whether to follow traditional way of publishnig depends only on user. Nevertheless, both ways have its
pros & cons. Definitely, the traditional way is a good point to start, since it uses the Gisquick plugin
|plugin| , which has been tested for a long time.
Anyway, please read short description of experimental way either to consider which one to follow.

2.1 **Preparing project**
"""""""""""""""""""""""""
How to proceed in QGIS.

2.2 **Uploading project**
"""""""""""""""""""""""""
How to upload prepared project created in plugin to server.

3. **Experimental publishing**
------------------------------
Experimental way of publishing is kind of innovative approach to Gisquick. New plugin |plugin2| is involved.
In comparison to traditional way, it allows user to easily edit published projects; every change made in
project in QGIS can be reflected in Gisquick by activating plugin which enables user to compare local and cloud
project's folders, layer by layer.

3.1 **Preparing project**
"""""""""""""""""""""""""
How to proceed in QGIS.

3.2 **Uploading project**
"""""""""""""""""""""""""
How to connect to the server directly from QGIS and upload project.

4. **Releasing project**
------------------------
Last few steps of publishing process are identical for both traditional and experimental way.

5. **User interface**
---------------------
Each component involved in UI is decribed in this chapter.

6. **Sample datasets**
----------------------
Basic information about datasets which were used for documentation.

7. **Other**
------------
Interesting links to video tutorials, used technologies or source code.

.. toctree::
   :maxdepth: 2

   user-manual/creating-account
   user-manual/traditional-publishing
   user-manual/experimental-publishing
   user-manual/releasing-publishing
   user-manual/user-interface
   user-manual/datasets
   other

.. figure:: ./img/example.svg

   Gisquick in action.

.. note:: Gisquick has been originally developed for `GIS.lab
   <http://gislab-npo.github.io/gislab/>`__ system with aim to produce
   generally usable web client interface. Later it was separated into
   a new independent project usable with or without GIS.lab
   infrastructure.