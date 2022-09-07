.. _CHARA_LANDING:

CHARA_LANDING
========================

.. code-block:: text

	CHARA_LANDING(eye, lip, CID, int)


Arguments
------------

* eye
* lip
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_LANDING",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1922,
	            "command": "play_sound",
	            "args": [
	                "SE_047"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1923,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "eye",
	                "lip",
	                "0",
	                "-90",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1924,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.05",
	                "0",
	                "200",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1925,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-200",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1926,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1927,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1928,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "90",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1929,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.2",
	                "0",
	                "90"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1930,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`play_sound`
* :ref:`CHARA_SET_POS_0`
* :ref:`mnu_move`
* :ref:`wait`
* :ref:`chara_fadein`
* :ref:`cmp_move`
