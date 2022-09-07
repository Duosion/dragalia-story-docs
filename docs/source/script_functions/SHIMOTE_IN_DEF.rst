.. _SHIMOTE_IN_DEF:

SHIMOTE_IN_DEF
========================

.. code-block:: text

	SHIMOTE_IN_DEF(CID)


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
	    "name": "SHIMOTE_IN_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2487,
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
	            "row": 2488,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.4",
	                "120",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2489,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2490,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.4"
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
