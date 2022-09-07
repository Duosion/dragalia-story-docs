.. _REPEL_KNIFE:

REPEL_KNIFE
========================

.. code-block:: text

	REPEL_KNIFE(CID, int)


Arguments
------------

* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "REPEL_KNIFE",
	    "args": [
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 4297,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4298,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_089"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4299,
	            "command": "play_sound",
	            "args": [
	                "SE_013"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4300,
	            "command": "c_swing_h_mid",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4301,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4302,
	            "command": "play_sound",
	            "args": [
	                "SE_013"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4303,
	            "command": "play_sound",
	            "args": [
	                "SE_047"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4304,
	            "command": "c_push_r",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4305,
	            "command": "wait",
	            "args": [
	                "0.9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4306,
	            "command": "play_sound",
	            "args": [
	                "SE_066"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4307,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4308,
	            "command": "wait",
	            "args": [
	                "0.8"
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
* :ref:`SCREEN_FLASH_WHITE_DEF`
* :ref:`set_BG_effect`
* :ref:`play_sound`
* :ref:`c_swing_h_mid`
* :ref:`wait`
* :ref:`c_push_r`
* :ref:`chara_face`
