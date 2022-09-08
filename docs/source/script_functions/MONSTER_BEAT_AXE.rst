.. _MONSTER_BEAT_AXE:

MONSTER_BEAT_AXE
========================

.. code-block:: text

	MONSTER_BEAT_AXE(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_BEAT_AXE(CID):
		WFOUT_SHORT()
		CHARA_SET(M, M, C, CID, 1)
		set_BG_effect(EFF_093)
		wait(0.1)
		play_sound(SE_116)
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
	    "name": "MONSTER_BEAT_AXE",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3729,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3730,
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
	            "row": 3731,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_093"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3732,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3733,
	            "command": "play_sound",
	            "args": [
	                "SE_116"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3734,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3735,
	            "command": "wait",
	            "args": [
	                "0.55"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3736,
	            "command": "play_sound",
	            "args": [
	                "SE_205"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3737,
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
