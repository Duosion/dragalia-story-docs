.. _MONSTER_BEAT_DAG:

MONSTER_BEAT_DAG
========================

.. code-block:: text

	MONSTER_BEAT_DAG(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_BEAT_DAG(CID):
		WFOUT_SHORT()
		CHARA_SET(M, M, C, CID, 1)
		set_BG_effect(EFF_090)
		wait(0.1)
		play_sound(SE_236)
		c_swing2_h_fast(CID)
		wait(0.55)
		play_sound(SE_205)
		MONSTER_BEAT_AFTER_0(CID)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`CHARA_SET`
* :ref:`set_BG_effect`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`
* :ref:`MONSTER_BEAT_AFTER_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_BEAT_DAG",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3717,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3718,
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
	            "row": 3719,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_090"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3720,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3721,
	            "command": "play_sound",
	            "args": [
	                "SE_236"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3722,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3723,
	            "command": "wait",
	            "args": [
	                "0.55"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3724,
	            "command": "play_sound",
	            "args": [
	                "SE_205"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3725,
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
