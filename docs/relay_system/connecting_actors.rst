.. _connecting-actors:

Connecting Actors
=================

.. image:: https://i.gyazo.com/179f83fad1659f823115aca4dabe966b.png

For relays to work, they must be have a connection to an actor's interaction component.
In this example, we'll have a locked door, with a button to unlock it. For these, I've placed
the door from *EasyInteractionSystem/Blueprints/Templates/BP_Door* and
*EasyInteractionSystem/Blueprints/Templates/BP_SimpleButton*.

.. note:: the door has the property "Start Locked" set to true.

Next, drag an :ref:'unlocker' into the scene, and look at the details panel.

.. image:: https://i.gyazo.com/db295b1f9618676159683c09f03e0f03.png

We'll need to set the listener to the button, and add a receiver (the door).
To do so, click the eye dropper and on your target, and cycle the Index until it connects to the
proper interactive component (if you only have one, the index of 0 will work).
Once you've set your components via the index or just setting the id, click the *Apply All IDs* button.
The whole process can be seen in the following clip:

.. image:: https://i.gyazo.com/84ea4fe2e75e617fc772b686c9394a7f.gif

Now, the button should be connected to the door, and pressing the button should unlock it.

.. image:: https://i.gyazo.com/fcdd1e150f6564cfb946aa497791b2ac.gif

And that's it! Now you can make more complex connections with this system!
