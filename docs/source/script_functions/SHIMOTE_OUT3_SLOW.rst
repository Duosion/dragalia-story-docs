.. _SHIMOTE_OUT3_SLOW:

SHIMOTE_OUT3_SLOW
========================

.. code-block:: text

	SHIMOTE_OUT3_SLOW(CID, CID2, CID3)


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
	    "name": "SHIMOTE_OUT3_SLOW",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2988,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2989,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2990,
	            "command": "NO_EMO",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2991,
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
	            "row": 2992,
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
	            "row": 2993,
	            "command": "mnu",
	            "args": [
	                "CID3",
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
	            "row": 2994,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2995,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2996,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2997,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
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
* :ref:`NO_EMO`
* :ref:`mnu`
* :ref:`wait`
* :ref:`chara_visible`
