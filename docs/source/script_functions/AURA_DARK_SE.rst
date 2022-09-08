.. _AURA_DARK_SE:

AURA_DARK_SE
========================

.. code-block:: text

	AURA_DARK_SE()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def AURA_DARK_SE():
		set_BG_effect(EFF_010, EFF_011)
		set_BG_effect_trigger(8, 8)
		play_sound(SE_031)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`play_sound`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "AURA_DARK_SE",
	    "args": [],
	    "commandList": [
	        {
	            "row": 4336,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_010",
	                "EFF_011"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4337,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8",
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4338,
	            "command": "play_sound",
	            "args": [
	                "SE_031"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
