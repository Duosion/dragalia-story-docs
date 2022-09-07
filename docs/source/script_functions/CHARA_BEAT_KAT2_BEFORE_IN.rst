.. _CHARA_BEAT_KAT2_BEFORE_IN:

CHARA_BEAT_KAT2_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_KAT2_BEFORE_IN(CID)


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
	    "name": "CHARA_BEAT_KAT2_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3902,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_089"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3903,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3904,
	            "command": "play_sound",
	            "args": [
	                "SE_234"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3905,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3906,
	            "command": "play_sound",
	            "args": [
	                "SE_234"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3907,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3908,
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

References
-------------
* :ref:`set_BG_effect`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`
