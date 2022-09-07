.. _EXP_EARTHSHAKE:

EXP_EARTHSHAKE
========================

.. code-block:: text

	EXP_EARTHSHAKE()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "EXP_EARTHSHAKE",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3138,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3139,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3140,
	            "command": "play_sound",
	            "args": [
	                "SE_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3141,
	            "command": "play_sound",
	            "args": [
	                "SE_034"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3142,
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

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`SCREEN_FLASH_WHITE_DEF`
* :ref:`play_sound`
* :ref:`effect_shake_bg`
