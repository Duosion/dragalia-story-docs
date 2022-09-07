.. _CHARA_BEAT_WIND_BEFORE_IN:

CHARA_BEAT_WIND_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_WIND_BEFORE_IN(CID)


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
	    "name": "CHARA_BEAT_WIND_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3984,
	            "command": "play_sound",
	            "args": [
	                "SE_242"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3985,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3986,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_037"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3987,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3988,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3989,
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
* :ref:`play_sound`
* :ref:`wait`
* :ref:`set_BG_effect`
* :ref:`c_swing2_h_fast`
