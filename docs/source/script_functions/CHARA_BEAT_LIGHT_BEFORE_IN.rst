.. _CHARA_BEAT_LIGHT_BEFORE_IN:

CHARA_BEAT_LIGHT_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_LIGHT_BEFORE_IN(CID)


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
	    "name": "CHARA_BEAT_LIGHT_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4011,
	            "command": "play_sound",
	            "args": [
	                "SE_244"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4012,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4013,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_038"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4014,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4015,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4016,
	            "command": "wait",
	            "args": [
	                "0.25"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`play_sound`
* :ref:`wait`
* :ref:`set_BG_effect`
* :ref:`c_swing2_h_fast`
