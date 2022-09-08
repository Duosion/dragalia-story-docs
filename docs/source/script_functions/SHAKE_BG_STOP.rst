.. _SHAKE_BG_STOP:

SHAKE_BG_STOP
========================

.. code-block:: text

	SHAKE_BG_STOP(SHAKE_VALUE, STOP_SEC)


Arguments
------------

* SHAKE_VALUE
* STOP_SEC

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	effect_shake_bg(SHAKE_VALUE, -1, STOP_SEC)

References
-------------
* :ref:`effect_shake_bg`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHAKE_BG_STOP",
	    "args": [
	        "SHAKE_VALUE",
	        "STOP_SEC"
	    ],
	    "commandList": [
	        {
	            "row": 5200,
	            "command": "effect_shake_bg",
	            "args": [
	                "SHAKE_VALUE",
	                "-1",
	                "STOP_SEC"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
