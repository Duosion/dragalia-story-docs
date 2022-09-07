.. _SHIMOTE_OUT2_SLOW:

SHIMOTE_OUT2_SLOW
========================

.. code-block:: text

	SHIMOTE_OUT2_SLOW(CID, CID2)


Arguments
------------

* CID
* CID2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHIMOTE_OUT2_SLOW",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 2895,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2896,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2897,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "1",
	                "1",
	                "0",
	                "0.8",
	                "0",
	                "0",
	                "0.8",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2898,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.8",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "1",
	                "1",
	                "0",
	                "0.8",
	                "0",
	                "0",
	                "0.8",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2899,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2900,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2901,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`NO_EMO`
* :ref:`mnu`
* :ref:`wait`
* :ref:`chara_visible`
