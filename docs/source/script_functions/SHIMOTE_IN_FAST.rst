.. _SHIMOTE_IN_FAST:

SHIMOTE_IN_FAST
========================

.. code-block:: text

	SHIMOTE_IN_FAST(CID)


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
	    "name": "SHIMOTE_IN_FAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2515,
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
	            "row": 2516,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "120",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2517,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2518,
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
