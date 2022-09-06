buildin__window_type
====================================

.. code-block:: text

    buildin__window_type(type)

Arguments
-----------

* type
    * Default Value: ``""``
    * Can be ``"MONOLOGUE"`` or ``"NORMAL"``

Description
-----------

This command sets the current story window type.

Sample
-----------

.. code-block:: json

    {
        "row": 66,
        "command": "window_type",
        "args": [
        "MONOLOGUE"
        ],
        "end": 1
    }