.. _BOTTOM_IN_DEF:

BOTTOM_IN_DEF
========================

.. code-block:: text

	BOTTOM_IN_DEF(CID)


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
	    "name": "BOTTOM_IN_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2543,
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
	            "row": 2544,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.4",
	                "0",
	                "120",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2545,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2546,
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
