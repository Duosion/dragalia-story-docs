.. _CHARA_BEAT_HIT_BEFORE_IN:

CHARA_BEAT_HIT_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_HIT_BEFORE_IN(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_BEAT_HIT_BEFORE_IN(CID):
		set_BG_effect(EFF_001)
		wait(0.05)
		play_sound(SE_230)
		wait(0.15)
		c_swing2_h_fast(CID)
		wait(0.25)

References
-------------
* :ref:`set_BG_effect`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_HIT_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4046,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4047,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4048,
	            "command": "play_sound",
	            "args": [
	                "SE_230"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4049,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4050,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4051,
	            "command": "wait",
	            "args": [
	                "0.25"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
