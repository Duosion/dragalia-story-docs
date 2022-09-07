.. _CHARA_BEAT_KAT_BEFORE_IN:

CHARA_BEAT_KAT_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_KAT_BEFORE_IN(CID)


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
	    "name": "CHARA_BEAT_KAT_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3895,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_090"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3896,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3897,
	            "command": "play_sound",
	            "args": [
	                "SE_234"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3898,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3899,
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
