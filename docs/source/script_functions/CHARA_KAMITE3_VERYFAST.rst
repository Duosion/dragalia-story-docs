.. _CHARA_KAMITE3_VERYFAST:

CHARA_KAMITE3_VERYFAST
========================

.. code-block:: text

	CHARA_KAMITE3_VERYFAST(eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3)


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

.. code-block:: python

	def CHARA_KAMITE3_VERYFAST(eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3):
		chara_visible(CID, false)
		chara_visible(CID2, false)
		chara_visible(CID3, false)
		chara_pos(CID, 1)
		chara_pos(CID2, 3)
		chara_pos(CID3, 2)
		chara_face(CID, int)
		chara_face(CID2, int2)
		chara_face(CID3, int3)
		eye1(CID, eye)
		eye1(CID2, eye2)
		eye1(CID3, eye3)
		lip1(CID, lip)
		lip1(CID2, lip2)
		lip1(CID3, lip3)
		KAMITE_IN_VERYFAST(CID)
		KAMITE_IN_VERYFAST(CID2)
		KAMITE_IN_VERYFAST(CID3)

References
-------------
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`chara_face`
* :ref:`eye1`
* :ref:`lip1`
* :ref:`KAMITE_IN_VERYFAST`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_KAMITE3_VERYFAST",
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
	            "row": 2244,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2245,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2246,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2247,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2248,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2249,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2250,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2251,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2252,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2253,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2254,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2255,
	            "command": "eye1",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2256,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2257,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2258,
	            "command": "lip1",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2259,
	            "command": "KAMITE_IN_VERYFAST",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2260,
	            "command": "KAMITE_IN_VERYFAST",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2261,
	            "command": "KAMITE_IN_VERYFAST",
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
