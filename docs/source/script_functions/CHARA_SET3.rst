.. _CHARA_SET3:

CHARA_SET3
========================

.. code-block:: text

	CHARA_SET3(eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3)


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
	    "name": "CHARA_SET3",
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
	            "row": 2195,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2196,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2197,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2198,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2199,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2200,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2201,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2202,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2203,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2204,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2205,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2206,
	            "command": "eye1",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2207,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2208,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2209,
	            "command": "lip1",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2210,
	            "command": "mnu_fade",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2211,
	            "command": "mnu_fade",
	            "args": [
	                "CID2",
	                "true",
	                "0.3",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2212,
	            "command": "mnu_fade",
	            "args": [
	                "CID3",
	                "true",
	                "0.3",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2213,
	            "command": "cmp_fade",
	            "args": [
	                "CID",
	                "0.3",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2214,
	            "command": "cmp_fade",
	            "args": [
	                "CID2",
	                "0.3",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2215,
	            "command": "cmp_fade",
	            "args": [
	                "CID3",
	                "0.3",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2216,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2217,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2218,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2219,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "true"
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
* :ref:`mnu_fade`
* :ref:`cmp_fade`
* :ref:`wait`
