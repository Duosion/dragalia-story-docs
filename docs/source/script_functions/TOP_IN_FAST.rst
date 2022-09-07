.. _TOP_IN_FAST:

TOP_IN_FAST
========================

.. code-block:: text

	TOP_IN_FAST(CID)


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
	    "name": "TOP_IN_FAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2564,
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
	            "row": 2565,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "0",
	                "-120",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2566,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2567,
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
