.. _CHANGE_DRAGON_LUMINE_DR:

CHANGE_DRAGON_LUMINE_DR
========================

.. code-block:: text

	CHANGE_DRAGON_LUMINE_DR()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHANGE_DRAGON_LUMINE_DR():
		set_BG_effect(EFF_072, EFF_073)
		set_BG_effect_trigger(9, 9)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHANGE_DRAGON_LUMINE_DR",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3053,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_072",
	                "EFF_073"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3054,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9",
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
