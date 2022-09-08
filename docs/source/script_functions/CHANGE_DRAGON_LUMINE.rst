.. _CHANGE_DRAGON_LUMINE:

CHANGE_DRAGON_LUMINE
========================

.. code-block:: text

	CHANGE_DRAGON_LUMINE()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	set_BG_effect(EFF_070, EFF_071)
	set_BG_effect_trigger(9, 9)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHANGE_DRAGON_LUMINE",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3042,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_070",
	                "EFF_071"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3043,
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
