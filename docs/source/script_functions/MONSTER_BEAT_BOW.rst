.. _MONSTER_BEAT_BOW:

MONSTER_BEAT_BOW
========================

.. code-block:: text

	MONSTER_BEAT_BOW(CID)


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
	    "name": "MONSTER_BEAT_BOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3753,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3754,
	            "command": "CHARA_SET",
	            "args": [
	                "M",
	                "M",
	                "C",
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3755,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_092"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3756,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3757,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_092",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3758,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3759,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3760,
	            "command": "play_sound",
	            "args": [
	                "SE_239"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3761,
	            "command": "wait",
	            "args": [
	                "0.55"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3762,
	            "command": "play_sound",
	            "args": [
	                "SE_205"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3763,
	            "command": "MONSTER_BEAT_AFTER_0",
	            "args": [
	                "CID"
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
* :ref:`WFOUT_SHORT`
* :ref:`CHARA_SET`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`set_BG_effect_speed`
* :ref:`wait`
* :ref:`c_swing2_h_fast`
* :ref:`play_sound`
* :ref:`MONSTER_BEAT_AFTER_0`
