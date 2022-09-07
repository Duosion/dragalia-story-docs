.. _CHARA_BEAT_DAG2_BEFORE_IN:

CHARA_BEAT_DAG2_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_DAG2_BEFORE_IN(CID)


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
	    "name": "CHARA_BEAT_DAG2_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3920,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_089"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3921,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3922,
	            "command": "play_sound",
	            "args": [
	                "SE_236"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3923,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3924,
	            "command": "play_sound",
	            "args": [
	                "SE_236"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3925,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3926,
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
