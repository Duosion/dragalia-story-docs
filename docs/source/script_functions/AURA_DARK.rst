.. _AURA_DARK:

AURA_DARK
========================

.. code-block:: text

	AURA_DARK()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def AURA_DARK():
		set_BG_effect(EFF_010, EFF_011)
		set_BG_effect_trigger(9, 8)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "AURA_DARK",
	    "args": [],
	    "commandList": [
	        {
	            "row": 4341,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_010",
	                "EFF_011"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4342,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9",
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
