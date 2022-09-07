.. _GUARD_KNIFE:

GUARD_KNIFE
========================

.. code-block:: text

	GUARD_KNIFE(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "GUARD_KNIFE",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4287,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4288,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_089"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4289,
	            "command": "play_sound",
	            "args": [
	                "SE_013"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4290,
	            "command": "c_swing_h_mid",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4291,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4292,
	            "command": "play_sound",
	            "args": [
	                "SE_013"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4293,
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
