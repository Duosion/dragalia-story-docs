.. _KAMITE_IN_VERYFAST:

KAMITE_IN_VERYFAST
========================

.. code-block:: text

	KAMITE_IN_VERYFAST(CID)


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
	    "name": "KAMITE_IN_VERYFAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2522,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2523,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "-120",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2524,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2525,
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
