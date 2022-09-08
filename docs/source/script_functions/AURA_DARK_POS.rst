.. _AURA_DARK_POS:

AURA_DARK_POS
========================

.. code-block:: text

	AURA_DARK_POS(X, Y)


Arguments
------------

* X
* Y

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	set_BG_effect(EFF_010, EFF_011)
	set_BG_effect_pos(EFF_010, X, Y)
	set_BG_effect_pos(EFF_011, X, Y)
	set_BG_effect_trigger(9, 8)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "AURA_DARK_POS",
	    "args": [
	        "X",
	        "Y"
	    ],
	    "commandList": [
	        {
	            "row": 4352,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_010",
	                "EFF_011"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4353,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_010",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4354,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_011",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4355,
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
