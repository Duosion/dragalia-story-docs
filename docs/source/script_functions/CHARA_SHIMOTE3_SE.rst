.. _CHARA_SHIMOTE3_SE:

CHARA_SHIMOTE3_SE
========================

.. code-block:: text

	CHARA_SHIMOTE3_SE(eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3, SE)


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
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

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
	play_sound(SE)
	wait(0.5)
	SHIMOTE_IN_DEF(CID)
	SHIMOTE_IN_DEF(CID2)
	BGMTUNE_DOWN_0(SE)
	SHIMOTE_IN_DEF(CID3)

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

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SHIMOTE3_SE",
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
	        "int3",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2386,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2387,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2388,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2389,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2390,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2391,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2392,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2393,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2394,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2395,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2396,
	            "command": "eye1",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2397,
	            "command": "eye1",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2398,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2399,
	            "command": "lip1",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2400,
	            "command": "lip1",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2401,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2402,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2403,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2404,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2405,
	            "command": "BGMTUNE_DOWN_0",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2406,
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
