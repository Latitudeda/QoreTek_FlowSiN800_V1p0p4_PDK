PDK structure
======================

Process Design Kit (PDK) is a tool for designated users to generate circuit layouts based on QoreTek FlowSiN 800nm design rules and technology settings.

``QoreTek_FlowSiN_800_V1p0p4_Latitudeda`` package includes three subfolders: ``components``, ``examples``, and ``technology``.

* ``components``

    * Fixed cells: All fixed cells, including ``bb_Bent_DC``, ``bb_Crossing``, ``bb_LinearEC``, ``bb_LinearGC``, etc, are named and designed by **QoreTek** and cannot be changed.

    * Parametrized cells (PCells): Designed by **Latitudeda**, including ``bend``, ``straight``, ``taper``, etc. Please see ``gpdk > components`` for more designed components by **Latitudeda**.

* ``examples``

    * ``tech_test.py`` : Tests that waveguide types, metal wire types, auto routing, and auto link function works normally under the PDK setting. Please see ``gpdk > examples`` for more circuit examples.

* ``technology``

    * Store the technology setting which matched the QoreTek FlowSiN 800nm design rules. We recommend users not to change the settings in technology folder.

    * See chapter ``Technology setting`` for more specific definition.

* ``QoreTek_FlowSiN_800_V1p0p4_Latitudeda.lyp``

    * This file allows layout tools e.g. Klayout to recognize the layer information when displaying gds file to the layout tool.

    .. image:: ../images/lyp.png
