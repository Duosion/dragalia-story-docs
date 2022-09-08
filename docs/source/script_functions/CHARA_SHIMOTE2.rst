.. _CHARA_SHIMOTE2:

CHARA_SHIMOTE2
========================

.. code-block:: text

	CHARA_SHIMOTE2(eye, lip, CID, int, eye2, lip2, CID2, int2)


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

.. code-block:: python

	def CHARA_SHIMOTE2(eye, lip, CID, int, eye2, lip2, CID2, int2):
		chara_visible(CID, false)
		chara_visible(CID2, false)
		chara_pos(CID, 3)
		chara_pos(CID2, 1)
		chara_face(CID, int)
		chara_face(CID2, int2)
		eye1(CID, eye)
		eye1(CID2, eye2)
		lip1(CID, lip)
		lip1(CID2, lip2)
		SHIMOTE_IN_DEF(CID)
		SHIMOTE_IN_DEF(CID2)

References
-------------
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`chara_face`
* :ref:`eye1`
* :ref:`lip1`
* :ref:`SHIMOTE_IN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SHIMOTE2",
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
	            "row": 2110,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2111,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2112,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2113,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2114,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2115,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2116,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2117,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2118,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2119,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2120,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2121,
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
