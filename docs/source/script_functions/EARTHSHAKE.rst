.. _EARTHSHAKE:

EARTHSHAKE
========================

.. code-block:: text

	EARTHSHAKE()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	WFOUT_DEF()
	SCREEN_FLASH_WHITE_DEF()
	play_sound(SE_034)
	effect_shake_bg(2, 1, 2)

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`SCREEN_FLASH_WHITE_DEF`
* :ref:`play_sound`
* :ref:`effect_shake_bg`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "EARTHSHAKE",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3131,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3132,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3133,
	            "command": "play_sound",
	            "args": [
	                "SE_034"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3134,
	            "command": "effect_shake_bg",
	            "args": [
	                "2",
	                "1",
	                "2"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
