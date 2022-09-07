.. _SHIMOTE_OUT3_DEF:

SHIMOTE_OUT3_DEF
========================

.. code-block:: text

	SHIMOTE_OUT3_DEF(CID, CID2, CID3)


Arguments
------------

* CID
* CID2
* CID3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHIMOTE_OUT3_DEF",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2975,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2976,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2977,
	            "command": "NO_EMO",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2978,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "1",
	                "0",
	                "0.4",
	                "0",
	                "0",
	                "0.4",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2979,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.4",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "1",
	                "0",
	                "0.4",
	                "0",
	                "0",
	                "0.4",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2980,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "0.4",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "1",
	                "0",
	                "0.4",
	                "0",
	                "0",
	                "0.4",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2981,
	            "command": "wait",
	            "args": [
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2982,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2983,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2984,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
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
