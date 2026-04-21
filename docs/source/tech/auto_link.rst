auto_link.py
=============

Define the auto link policies between different waveguide type.

For example:

``(type(WG.Strip.C.WIRE) >> type(WG.Strip.C.WIRE), fpt.StraightPrefer(WG.Strip.C.WIRE), fpt.BendUsing(WG.Strip.C.WIRE.BEND_CIRCULAR))``

It means that when the start and end waveguide are both ``WG.Strip.C.WIRE``, the automated waveguide type for routing will be ``WG.Strip.C.WIRE`` and an automated bend ``WG.Strip.C.WIRE.BEND_CIRCULAR`` will be added.


Users are allowed to define and set ``DEFAULT`` to their own specific linking policy.

