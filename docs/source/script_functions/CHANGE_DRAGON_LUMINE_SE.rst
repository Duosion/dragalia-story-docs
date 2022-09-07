.. _CHANGE_DRAGON_LUMINE_SE:

CHANGE_DRAGON_LUMINE_SE
========================

.. code-block:: text

	CHANGE_DRAGON_LUMINE_SE()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHANGE_DRAGON_LUMINE_SE",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3047,
	            "command": "play_sound",
	            "args": [
	                "SE_209"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3048,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_070",
	                "EFF_071"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3049,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8",
	                "8"
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
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
