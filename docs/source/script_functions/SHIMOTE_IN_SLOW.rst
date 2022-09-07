.. _SHIMOTE_IN_SLOW:

SHIMOTE_IN_SLOW
========================

.. code-block:: text

	SHIMOTE_IN_SLOW(CID)


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
	    "name": "SHIMOTE_IN_SLOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2501,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.05",
	                "-120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2502,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "120",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2503,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2504,
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
