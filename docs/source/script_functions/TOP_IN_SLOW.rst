.. _TOP_IN_SLOW:

TOP_IN_SLOW
========================

.. code-block:: text

	TOP_IN_SLOW(CID)


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
	    "name": "TOP_IN_SLOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2550,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.05",
	                "0",
	                "120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2551,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "0",
	                "-120",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2552,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2553,
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
