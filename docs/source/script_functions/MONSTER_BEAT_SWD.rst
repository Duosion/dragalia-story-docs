.. _MONSTER_BEAT_SWD:

MONSTER_BEAT_SWD
========================

.. code-block:: text

	MONSTER_BEAT_SWD(CID)


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
	    "name": "MONSTER_BEAT_SWD",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3693,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3694,
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
	            "row": 3695,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_090"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3696,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3697,
	            "command": "play_sound",
	            "args": [
	                "SE_233"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3698,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3699,
	            "command": "wait",
	            "args": [
	                "0.55"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3700,
	            "command": "play_sound",
	            "args": [
	                "SE_205"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3701,
	            "command": "MONSTER_BEAT_AFTER_0",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`CHARA_SET`
* :ref:`set_BG_effect`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`
* :ref:`MONSTER_BEAT_AFTER_0`
