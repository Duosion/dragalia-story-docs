.. _SHIMOTE_OUT2_DEF:

SHIMOTE_OUT2_DEF
========================

.. code-block:: text

	SHIMOTE_OUT2_DEF(CID, CID2)


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
	    "name": "SHIMOTE_OUT2_DEF",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 2885,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2886,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2887,
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
	            "row": 2888,
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
	            "row": 2889,
	            "command": "wait",
	            "args": [
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2890,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2891,
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
