AdvancedSDL
=======================================

Import QoreTek_FlowSiN_800_V1p0p4_Latitudeda PDK into AdvancedSDL
*******************************************

Copy the **QoreTek_FlowSiN_800_V1p0p4_Latitudeda PDK** folder to the **AdvancedSDL** installation path: ``...\AdvancedSDL\Python\Lib\site-packages``. It can also be placed in other paths that do not contain special symbols such as Chinese characters and Spaces, so that python does not fail to identify the path.

.. image:: ../images/ASDL_0.png

Click ``PDK`` on the top toolbar of **AdvancedSDL** and select ``Open PDK Symbol Design``.

.. image:: ../images/ASDL_1.png

Locate and select the ``QoreTek_FlowSiN_800_V1p0p4_Latitudeda`` PDK folder.

.. image:: ../images/ASDL_2.png

After the import is complete, you will see the **QoreTek_FlowSiN_800_V1p0p4_Latitudeda** PDK component library on the left.

.. image:: ../images/ASDL_3.png

Click ``File`` and then click ``New Project``.

.. image:: ../images/ASDL_4.png

Enter the project name and path, select ``QoreTek_FlowSiN_800_V1p0p4_Latitudeda`` PDK in the PDK column, and click ``OK``.

.. image:: ../images/ASDL_5.png

Wait for the contents of ``Import QoreTek_FlowSiN_800_V1p0p4_Latitudeda pdk symbols succeed`` to appear in the output.

.. image:: ../images/ASDL_6.png

Right-click on the ``circuits`` of the project, click ``New Circuit``, type ``circuit name`` and click ``OK``.

.. image:: ../images/ASDL_7.png

Drag components to the center region. Click on the component, the parameters of the component can be adjusted on the right side.

.. image:: ../images/ASDL_8.png

Once the parameters are set, connect the ports to route the components and click SDL in the upper right.

.. image:: ../images/ASDL_10.png

The corresponding layout is displayed in the ``Layout View``. And it generates python layout code called ``Generated-Script.py``, which can be run and used in **PhotoCAD**.

.. image:: ../images/ASDL_11.png

The ``Generated-Script.py`` can be run in **PhotoCAD** and modified to create a new layout. The script is saved in the project's Temp folder.

.. image:: ../images/ASDL_12.png

You can also easily import a specific component to **AdvancedSDL** on **PhotoCAD** using ``fp.export_schematic``. See ``gpdk > examples`` for more information.