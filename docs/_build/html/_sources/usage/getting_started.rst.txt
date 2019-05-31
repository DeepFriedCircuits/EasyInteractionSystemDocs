Getting Started
===============

Hopefully, you'll find getting interactive elements in you game easy and painless.

---------------
Core Components
---------------

To have functional interactions, you only need two components:

* The :ref:`interaction-handler` which handles the players input and interactions.
* The :ref:`interactive` which is the actual component that the interactive actors will use to receive the events.

Included also, are some helper blueprints to allow for quick and intuitive level design:

* The :ref:`relay-actor` which is the base class for interactive to interactive communication.
* The :ref:`state-forcer` which is the base class for one interactive to trigger a specific state in another interactive.
* The :ref:`unlocker` which works similar to the state forcer, but is only for locking/unlocking.
