.. _CHANGE_DRAGON_LUMINE_DR_SE:

CHANGE_DRAGON_LUMINE_DR_SE
========================

.. code-block:: text

	CHANGE_DRAGON_LUMINE_DR_SE()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHANGE_DRAGON_LUMINE_DR_SE():
		play_sound(SE_209)
		set_BG_effect(EFF_072, EFF_073)
		set_BG_effect_trigger(8, 8)

References
-------------
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHANGE_DRAGON_LUMINE_DR_SE",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3058,
	            "command": "play_sound",
	            "args": [
	                "SE_209"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3059,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_072",
	                "EFF_073"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3060,
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
