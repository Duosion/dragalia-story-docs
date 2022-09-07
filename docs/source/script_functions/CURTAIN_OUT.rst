.. _CURTAIN_OUT:

CURTAIN_OUT
========================

.. code-block:: text

	CURTAIN_OUT()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CURTAIN_OUT",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1679,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_107"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1680,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1681,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
