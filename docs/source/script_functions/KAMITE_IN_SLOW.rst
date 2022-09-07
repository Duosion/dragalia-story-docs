.. _KAMITE_IN_SLOW:

KAMITE_IN_SLOW
========================

.. code-block:: text

	KAMITE_IN_SLOW(CID)


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
	    "name": "KAMITE_IN_SLOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2494,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.05",
	                "120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2495,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "-120",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2496,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2497,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.6"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`wait`
* :ref:`chara_fadein`
