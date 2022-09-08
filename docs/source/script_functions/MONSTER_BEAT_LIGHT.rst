.. _MONSTER_BEAT_LIGHT:

MONSTER_BEAT_LIGHT
========================

.. code-block:: text

	MONSTER_BEAT_LIGHT(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_BEAT_LIGHT(CID):
		WFOUT_SHORT()
		CHARA_SET(M, M, C, CID, 1)
		play_sound(SE_244)
		wait(0.3)
		set_BG_effect(EFF_038)
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
	    "name": "MONSTER_BEAT_LIGHT",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3767,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3768,
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
	            "row": 3769,
	            "command": "play_sound",
	            "args": [
	                "SE_244"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3770,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3771,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_038"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3772,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3773,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3774,
	            "command": "wait",
	            "args": [
	                "0.55"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3775,
	            "command": "play_sound",
	            "args": [
	                "SE_205"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3776,
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
