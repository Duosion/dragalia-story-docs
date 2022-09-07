.. _SHOUT_0_EFF:

SHOUT_0_EFF
========================

.. code-block:: text

	SHOUT_0_EFF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_0_EFF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3207,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3208,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3209,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3210,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "9"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_speed`
* :ref:`set_BG_effect_trigger`
