.. _CHARA_SHIMOTE2_SE:

CHARA_SHIMOTE2_SE
========================

.. code-block:: text

	CHARA_SHIMOTE2_SE(eye, lip, CID, int, eye2, lip2, CID2, int2, SE)


Arguments
------------

* eye
* lip
* CID
* int
* eye2
* lip2
* CID2
* int2
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SHIMOTE2_SE",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int",
	        "eye2",
	        "lip2",
	        "CID2",
	        "int2",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2174,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2175,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2176,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2177,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2178,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2179,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2180,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2181,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2182,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2183,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2184,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2185,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2186,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2187,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2188,
	            "command": "BGMTUNE_DOWN_0",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2189,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID2"
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
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`chara_face`
* :ref:`eye1`
* :ref:`lip1`
* :ref:`play_sound`
* :ref:`wait`
* :ref:`SHIMOTE_IN_DEF`
* :ref:`BGMTUNE_DOWN_0`
