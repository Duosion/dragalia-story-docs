.. _KAMITE_IN_FAST:

KAMITE_IN_FAST
========================

.. code-block:: text

	KAMITE_IN_FAST(CID)


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
	    "name": "KAMITE_IN_FAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2508,
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
	            "row": 2509,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "-120",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2510,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2511,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.3"
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
