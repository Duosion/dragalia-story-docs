.. _CHARA_KAMITE3:

CHARA_KAMITE3
========================

.. code-block:: text

	CHARA_KAMITE3(eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3)


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
* eye3
* lip3
* CID3
* int3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_KAMITE3",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int",
	        "eye2",
	        "lip2",
	        "CID2",
	        "int2",
	        "eye3",
	        "lip3",
	        "CID3",
	        "int3"
	    ],
	    "commandList": [
	        {
	            "row": 2223,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2224,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2225,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2226,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2227,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2228,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2229,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2230,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2231,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2232,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2233,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2234,
	            "command": "eye1",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2235,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2236,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2237,
	            "command": "lip1",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2238,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2239,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2240,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID3"
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
* :ref:`KAMITE_IN_DEF`
