.. _SHIMOTE_IN_VERYFAST:

SHIMOTE_IN_VERYFAST
========================

.. code-block:: text

	SHIMOTE_IN_VERYFAST(CID)


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
	    "name": "SHIMOTE_IN_VERYFAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2529,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "-120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2530,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "120",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2531,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2532,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.2"
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
