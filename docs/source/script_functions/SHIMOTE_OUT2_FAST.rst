.. _SHIMOTE_OUT2_FAST:

SHIMOTE_OUT2_FAST
========================

.. code-block:: text

	SHIMOTE_OUT2_FAST(CID, CID2)


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
	    "name": "SHIMOTE_OUT2_FAST",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 2905,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2906,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2907,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.3",
	                "1",
	                "1",
	                "0",
	                "0.3",
	                "0",
	                "0",
	                "0.3",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2908,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.3",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.3",
	                "1",
	                "1",
	                "0",
	                "0.3",
	                "0",
	                "0",
	                "0.3",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2909,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2910,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2911,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
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
