.. _BOTTOM_IN_SLOW:

BOTTOM_IN_SLOW
========================

.. code-block:: text

	BOTTOM_IN_SLOW(CID)


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
	    "name": "BOTTOM_IN_SLOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2557,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.05",
	                "0",
	                "-120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2558,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "0",
	                "120",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2559,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2560,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.6"
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
* :ref:`mnu_move`
* :ref:`wait`
* :ref:`chara_fadein`
