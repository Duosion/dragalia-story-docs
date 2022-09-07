.. _CHARA_KAMITE_VERYFAST_SE:

CHARA_KAMITE_VERYFAST_SE
========================

.. code-block:: text

	CHARA_KAMITE_VERYFAST_SE(eye, lip, POS, CID, int, SE)


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
	    "name": "CHARA_KAMITE_VERYFAST_SE",
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
	            "row": 1877,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1878,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1879,
	            "command": "BGMTUNE_DOWN_0",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1880,
	            "command": "CHARA_KAMITE_VERYFAST",
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

Sample
-------------

.. code-block:: json

	{}

References
-------------
* :ref:`play_sound`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`
* :ref:`CHARA_KAMITE_VERYFAST`
