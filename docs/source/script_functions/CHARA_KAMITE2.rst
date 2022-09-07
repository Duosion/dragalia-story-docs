.. _CHARA_KAMITE2:

CHARA_KAMITE2
========================

.. code-block:: text

	CHARA_KAMITE2(eye, lip, CID, int, eye2, lip2, CID2, int2)


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
	    "name": "CHARA_KAMITE2",
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
	            "row": 2095,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2096,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2097,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2098,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2099,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2100,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2101,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2102,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2103,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2104,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2105,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2106,
	            "command": "KAMITE_IN_DEF",
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
* :ref:`KAMITE_IN_DEF`
