.. _SHIMOTE_OUT_FAST_SE:

SHIMOTE_OUT_FAST_SE
========================

.. code-block:: text

	SHIMOTE_OUT_FAST_SE(CID, SE)


Arguments
------------

* CID
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHIMOTE_OUT_FAST_SE",
	    "args": [
	        "CID",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2806,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2807,
	            "command": "SHIMOTE_OUT_FAST",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2808,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2809,
	            "command": "BGMTUNE_DOWN_0",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`play_sound`
* :ref:`SHIMOTE_OUT_FAST`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`
