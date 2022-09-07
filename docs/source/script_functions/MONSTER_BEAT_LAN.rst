.. _MONSTER_BEAT_LAN:

MONSTER_BEAT_LAN
========================

.. code-block:: text

	MONSTER_BEAT_LAN(CID)


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
	    "name": "MONSTER_BEAT_LAN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3741,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3742,
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
	            "row": 3743,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_090"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3744,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3745,
	            "command": "play_sound",
	            "args": [
	                "SE_238"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3746,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3747,
	            "command": "wait",
	            "args": [
	                "0.55"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3748,
	            "command": "play_sound",
	            "args": [
	                "SE_205"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3749,
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
* :ref:`wait`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`
* :ref:`MONSTER_BEAT_AFTER_0`
