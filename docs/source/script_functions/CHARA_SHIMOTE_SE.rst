.. _CHARA_SHIMOTE_SE:

CHARA_SHIMOTE_SE
========================

.. code-block:: text

	CHARA_SHIMOTE_SE(eye, lip, POS, CID, int, SE)


Arguments
------------

* eye
* lip
* POS
* CID
* int
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SHIMOTE_SE",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 1884,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1885,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1886,
	            "command": "BGMTUNE_DOWN_0",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1887,
	            "command": "CHARA_SHIMOTE",
	            "args": [
	                "eye",
	                "lip",
	                "POS",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`play_sound`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`
* :ref:`CHARA_SHIMOTE`
