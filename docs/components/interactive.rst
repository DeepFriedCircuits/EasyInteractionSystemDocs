.. _interactive:

BP_Interactive
==============

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Interactive Component Properties
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The interactive component can be tweaked and modified to suite your needs.
This page should serve as quick cheat sheet explaining each.

--------
Settings
--------

.. figure:: https://i.gyazo.com/01a3764e8136352882b70471f4608b09.png
   :align: center


*Interactive ID*
  This setting will be used by the relay system, to determine which interactive it was connected to.

*Interaction Text*
  Use this text to display in your UI.

*State*
  The current state of the Interactive. See :ref:`interactive-states`.

*Locked Text*
  Displayed text when

*One Shot*
  Determines if the interactive only be interacted once.

*Looping*
  Should the interaction repeat itself as long as the player holds interact?

*Duration*
  How long should it take to complete the interaction.

*Interactive Mask*
  The type of interactive this is. See :ref:`handler-settings` property **Scan Filter**.

-------
Caching
-------

.. figure:: https://i.gyazo.com/dbf2404304919829462b71ff3dc68da6.png
  :align: center

*Cache Progress*
  Keeps the current progress of the interaction store for later. So if you were half way through with
  a long interaction, when you release the button and then interact again, the progress will be still
  half if this property is true.

*Decay Cached Progress*
  if Cache Progress is true, this will return the progress to zero, at the same rate as the duration allows.

-----
Audio
-----

.. figure:: https://i.gyazo.com/c7fbaabb36922d04620e90aa8cb44e8a.png
  :align: center

*Interaction Sound*
  The sound made on a successful interaction.

*Interaction Failed Sound*
  The sound made when an interaction failed.
