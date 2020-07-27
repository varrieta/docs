Deleting objects
================

You can delete point or line objects (with all associated objects) through the **vw_qgep_(cover/reach)** layers.
You can also pick and delete only a specific object (e.g. cover).

Delete Reaches
--------------
* Select **vw_qgep_reach** and change to edit mode.
* Select the reach(es) you want to delete. You can click on an object or draw an area.

.. figure:: images/select_tool.jpg

* Use the top meu **Edit** --> **Delete Selected** to delete.

.. figure:: images/delete_reach.jpg

.. note:: The easiest way is to simply press the **Delete** key on your keyboard.
  Another way is to press the **Delete** button located in the **Digitizing toolbar**.

  .. figure:: images/delete_button.jpg
  
  Depending on how you customized QGIS the **Digitizing toolbar** may be hidden or located
  elsewhere.

* Deselect the edit mode and confirm changes to layer. All changes will be saved to database.

.. figure:: images/delete_reach_confirm.jpg


Delete Manholes and other Waste water Structures
------------------------------------------------

* Select **vw_qgep_cover** and change to edit mode
* Select the objects (**manholes**, **special structures** etc.) you want to delete
* Use **Edit** --> **Delete Selected** to delete. 
* Stop the editing mode and confirm changes to layer. All changes will be saved to database.

Delete Covers
-------------

* Select **vw_qgep_cover** and change to edit mode
* Select the object (**manholes**, **special structures** etc.) to which you want the cover deleted
* Use the **Identify Features** tool to open the form
* Switch to the covers tab 
* Select the cover(s) you want to delete
* Click the red x button to delete the covers

.. figure:: images/delete_covers.jpg

* Click save on the form
* Deselect the edit mode and confirm changes to layer. All changes will be saved to database.

Delete structure detailed geometry
----------------------------------

* Select **od_wastewater_structure** and change to edit mode
* Select the detailed geometry you want to delete
* Use the top menu **Edit** --> **Delete Part** to delete. 
* Stop the editing mode and confirm changes to layer. All changes will be saved to database.

**WARNING**: do not use the the **Delete selected" tool, otherwise the whole structure will be deleted.

Delete Structure parts
----------------------

* Select **vw_qgep_cover** and change to edit mode
* Select the object (**manholes**, **special structures** etc.) you want to delete the cover
* Use the **Identify Features** tool to open the form
* Switch to the structure parts tab
* Select the structure part you want to delete
* Click the read x to delete the covers
* Click save on the form
* Stop the editing mode and confirm changes to layer. All changes will be saved to database.
