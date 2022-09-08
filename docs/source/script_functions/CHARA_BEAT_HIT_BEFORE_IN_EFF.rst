.. _CHARA_BEAT_HIT_BEFORE_IN_EFF:

CHARA_BEAT_HIT_BEFORE_IN_EFF
========================

.. code-block:: text

	CHARA_BEAT_HIT_BEFORE_IN_EFF(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	set_BG_effect(1, 1, EFF_001)
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
	    "name": "CHARA_BEAT_HIT_BEFORE_IN_EFF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4055,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4056,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4057,
	            "command": "play_sound",
	            "args": [
	                "SE_230"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4058,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4059,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4060,
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
