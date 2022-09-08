.. _CHARA_SHIMOTE3:

CHARA_SHIMOTE3
========================

.. code-block:: text

	CHARA_SHIMOTE3(eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3)


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

	def CHARA_SHIMOTE3(eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3):
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
		SHIMOTE_IN_DEF(CID)
		SHIMOTE_IN_DEF(CID2)
		SHIMOTE_IN_DEF(CID3)

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
	    "name": "CHARA_SHIMOTE3",
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
	            "row": 2265,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2266,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2267,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2268,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2269,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2270,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2271,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2272,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2273,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2274,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2275,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2276,
	            "command": "eye1",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2277,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2278,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2279,
	            "command": "lip1",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2280,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2281,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2282,
	            "command": "SHIMOTE_IN_DEF",
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
