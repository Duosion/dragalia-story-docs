.. _THUNDER:

THUNDER
========================

.. code-block:: text

	THUNDER()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "THUNDER",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3146,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3147,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3148,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3149,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3150,
	            "command": "fade_color",
	            "args": [
	                "0.1",
	                "255",
	                "255",
	                "255",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3151,
	            "command": "play_sound",
	            "args": [
	                "SE_078"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3152,
	            "command": "fade_color",
	            "args": [
	                "1.5",
	                "255",
	                "255",
	                "255",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3153,
	            "command": "wait",
	            "args": [
	                "0.5"
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
* :ref:`wait`
* :ref:`SCREEN_FLASH_WHITE_DEF`
* :ref:`fade_color`
* :ref:`play_sound`
