.. _TOP_IN_VERYFAST:

TOP_IN_VERYFAST
========================

.. code-block:: text

	TOP_IN_VERYFAST(CID)


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
	    "name": "TOP_IN_VERYFAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2578,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0",
	                "120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2579,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-120",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2580,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2581,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.2"
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
