.. _SHAKE_CH_STOP:

SHAKE_CH_STOP
========================

.. code-block:: text

	SHAKE_CH_STOP(SHAKE_VALUE, STOP_SEC)


Arguments
------------

* SHAKE_VALUE
* STOP_SEC

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHAKE_CH_STOP",
	    "args": [
	        "SHAKE_VALUE",
	        "STOP_SEC"
	    ],
	    "commandList": [
	        {
	            "row": 5211,
	            "command": "effect_shake_chara",
	            "args": [
	                "SHAKE_VALUE",
	                "-1",
	                "STOP_SEC"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`effect_shake_chara`
