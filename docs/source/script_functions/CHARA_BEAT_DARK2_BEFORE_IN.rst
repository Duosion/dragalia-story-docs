.. _CHARA_BEAT_DARK2_BEFORE_IN:

CHARA_BEAT_DARK2_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_DARK2_BEFORE_IN(CID)


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
	    "name": "CHARA_BEAT_DARK2_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4029,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_040"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4030,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4031,
	            "command": "play_sound",
	            "args": [
	                "SE_044"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4032,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4033,
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
* :ref:`set_BG_effect`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`
