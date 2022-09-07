.. _KAMITE_IN_ZIG:

KAMITE_IN_ZIG
========================

.. code-block:: text

	KAMITE_IN_ZIG(CID)


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
	    "name": "KAMITE_IN_ZIG",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2592,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.05",
	                "160",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2593,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.15",
	                "-20",
	                "20",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2594,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "-40",
	                "-40",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2595,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "-40",
	                "40",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2596,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "-40",
	                "-40",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2597,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.15",
	                "-20",
	                "20",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2598,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.25",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2599,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2600,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.5"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
* :ref:`wait`
* :ref:`chara_fadein`
