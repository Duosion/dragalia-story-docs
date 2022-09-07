.. _CHARA_BEAT_LAN_BEFORE_IN:

CHARA_BEAT_LAN_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_LAN_BEFORE_IN(CID)


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
	    "name": "CHARA_BEAT_LAN_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3938,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_090"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3939,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3940,
	            "command": "play_sound",
	            "args": [
	                "SE_238"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3941,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3942,
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
