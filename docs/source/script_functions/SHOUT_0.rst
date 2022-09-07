.. _SHOUT_0:

SHOUT_0
========================

.. code-block:: text

	SHOUT_0()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_0",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3200,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3201,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3202,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3203,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_speed`
* :ref:`set_BG_effect_trigger`
