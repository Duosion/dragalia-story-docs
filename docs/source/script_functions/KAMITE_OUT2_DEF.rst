.. _KAMITE_OUT2_DEF:

KAMITE_OUT2_DEF
========================

.. code-block:: text

	KAMITE_OUT2_DEF(CID, CID2)


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
	    "name": "KAMITE_OUT2_DEF",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 2855,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2856,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2857,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "120",
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
	            "row": 2858,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.4",
	                "120",
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
	            "row": 2859,
	            "command": "wait",
	            "args": [
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2860,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2861,
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
