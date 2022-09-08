.. _MONSTER_BEAT_DARK:

MONSTER_BEAT_DARK
========================

.. code-block:: text

	MONSTER_BEAT_DARK(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_BEAT_DARK(CID):
		WFOUT_SHORT()
		CHARA_SET(M, M, C, CID, 1)
		play_sound(SE_245)
		wait(0.3)
		set_BG_effect(EFF_039)
		wait(0.2)
		c_swing2_h_fast(CID)
		wait(0.55)
		play_sound(SE_205)
		MONSTER_BEAT_AFTER_0(CID)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`CHARA_SET`
* :ref:`play_sound`
* :ref:`wait`
* :ref:`set_BG_effect`
* :ref:`c_swing2_h_fast`
* :ref:`MONSTER_BEAT_AFTER_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_BEAT_DARK",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3780,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3781,
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
	            "row": 3782,
	            "command": "play_sound",
	            "args": [
	                "SE_245"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3783,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3784,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_039"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3785,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3786,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3787,
	            "command": "wait",
	            "args": [
	                "0.55"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3788,
	            "command": "play_sound",
	            "args": [
	                "SE_205"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3789,
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
