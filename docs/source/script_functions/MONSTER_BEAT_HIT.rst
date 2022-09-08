.. _MONSTER_BEAT_HIT:

MONSTER_BEAT_HIT
========================

.. code-block:: text

	MONSTER_BEAT_HIT(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_BEAT_HIT(CID):
		WFOUT_SHORT()
		CHARA_SET(M, M, C, CID, 1)
		set_BG_effect(EFF_001)
		wait(0.05)
		play_sound(SE_230)
		wait(0.15)
		c_swing2_h_fast(CID)
		wait(0.25)
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
	    "name": "MONSTER_BEAT_HIT",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3793,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3794,
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
	            "row": 3795,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3796,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3797,
	            "command": "play_sound",
	            "args": [
	                "SE_230"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3798,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3799,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3800,
	            "command": "wait",
	            "args": [
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3801,
	            "command": "play_sound",
	            "args": [
	                "SE_205"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3802,
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
