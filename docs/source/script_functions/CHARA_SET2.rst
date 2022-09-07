.. _CHARA_SET2:

CHARA_SET2
========================

.. code-block:: text

	CHARA_SET2(eye, lip, CID, int, eye2, lip2, CID2, int2)


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

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SET2",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int",
	        "eye2",
	        "lip2",
	        "CID2",
	        "int2"
	    ],
	    "commandList": [
	        {
	            "row": 2075,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2076,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2077,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2078,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2079,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2080,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2081,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2082,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2083,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2084,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2085,
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
	            "row": 2086,
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
	            "row": 2087,
	            "command": "cmp_fade",
	            "args": [
	                "CID",
	                "0.3",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2088,
	            "command": "cmp_fade",
	            "args": [
	                "CID2",
	                "0.3",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2089,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2090,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2091,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
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
