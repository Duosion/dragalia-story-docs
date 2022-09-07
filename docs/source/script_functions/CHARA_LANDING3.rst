.. _CHARA_LANDING3:

CHARA_LANDING3
========================

.. code-block:: text

	CHARA_LANDING3(eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3)


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
	    "name": "CHARA_LANDING3",
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
	            "row": 2434,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2435,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2436,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2437,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2438,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2439,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2440,
	            "command": "play_sound",
	            "args": [
	                "SE_047"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2441,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "eye",
	                "lip",
	                "-200",
	                "-90",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2442,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.05",
	                "0",
	                "200",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2443,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-200",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2444,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2445,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2446,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "90",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2447,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.2",
	                "0",
	                "90"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2448,
	            "command": "play_sound",
	            "args": [
	                "SE_047"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2449,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "eye2",
	                "lip2",
	                "200",
	                "-90",
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2450,
	            "command": "mnu_move",
	            "args": [
	                "CID2",
	                "true",
	                "0.05",
	                "0",
	                "200",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2451,
	            "command": "mnu_move",
	            "args": [
	                "CID2",
	                "false",
	                "0.25",
	                "0",
	                "-200",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2452,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2453,
	            "command": "chara_fadein",
	            "args": [
	                "CID2",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2454,
	            "command": "mnu_move",
	            "args": [
	                "CID2",
	                "true",
	                "0.2",
	                "0",
	                "90",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2455,
	            "command": "cmp_move",
	            "args": [
	                "CID2",
	                "0.2",
	                "0",
	                "90"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2456,
	            "command": "play_sound",
	            "args": [
	                "SE_047"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2457,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "eye3",
	                "lip3",
	                "0",
	                "-90",
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2458,
	            "command": "mnu_move",
	            "args": [
	                "CID3",
	                "true",
	                "0.05",
	                "0",
	                "200",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2459,
	            "command": "mnu_move",
	            "args": [
	                "CID3",
	                "false",
	                "0.25",
	                "0",
	                "-200",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2460,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2461,
	            "command": "chara_fadein",
	            "args": [
	                "CID3",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2462,
	            "command": "mnu_move",
	            "args": [
	                "CID3",
	                "true",
	                "0.2",
	                "0",
	                "90",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2463,
	            "command": "cmp_move",
	            "args": [
	                "CID3",
	                "0.2",
	                "0",
	                "90"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`chara_visible`
* :ref:`chara_face`
* :ref:`play_sound`
* :ref:`CHARA_SET_POS_0`
* :ref:`mnu_move`
* :ref:`wait`
* :ref:`chara_fadein`
* :ref:`cmp_move`
