.. _AURA_DARK_POS_SE:

AURA_DARK_POS_SE
========================

.. code-block:: text

	AURA_DARK_POS_SE(X, Y)


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
	set_BG_effect_trigger(8, 8)
	play_sound(SE_031)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_trigger`
* :ref:`play_sound`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "AURA_DARK_POS_SE",
	    "args": [
	        "X",
	        "Y"
	    ],
	    "commandList": [
	        {
	            "row": 4345,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_010",
	                "EFF_011"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4346,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_010",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4347,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_011",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4348,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8",
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4349,
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
