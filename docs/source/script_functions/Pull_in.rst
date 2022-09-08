.. _Pull_in:

Pull_in
========================

.. code-block:: text

	Pull_in(eye1, lip1, CID, int, eye2, lip2, CID2, int2, front)


Arguments
------------

* eye1
* lip1
* CID
* int
* eye2
* lip2
* CID2
* int2
* front

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	c_face(eye1, lip1, CID, int)
	mnu_move(CID, true, 0.3, 120, 0, EaseOutSine)
	cmp_move(CID, 0.3, 120, 0)
	wait(0.3)
	CHARA_SET_0(eye2, lip2, R, CID2, int2)
	chara_pos(CID2, 360, 0)
	play_sound(SE_047)
	if front == 1:
		mnu_move(CID, true, 0.3, -90, 0, EaseOutSine)
		mnu(CID2, true, 0.3, -90, 0, EaseOutSine, 0.3, 1.0, 1.0, EaseOutSine, 0.3, 0, EaseOutSine, 0.3, 1, EaseOutSine)
		cmp_move(CID, 0.3, -90, 0)
		cmp(CID2, 0.3, -90, 0, 1, 1, 0, 1)
		wait(0.7)
		play_sound(SE_047)
		mnu_move(CID, true, 0.3, -90, 0, EaseOutSine)
		mnu_move(CID2, true, 0.3, -90, 0, EaseOutSine)
		cmp_move(CID, 0.3, -90, 0)
		cmp_move(CID2, 0.3, -90, 0)
	else:
		mnu(CID2, true, 0.3, -90, 0, EaseOutSine, 0.3, 1.0, 1.0, EaseOutSine, 0.3, 0, EaseOutSine, 0.3, 1, EaseOutSine)
		mnu_move(CID, true, 0.3, -90, 0, EaseOutSine)
		cmp(CID2, 0.3, -90, 0, 1, 1, 0, 1)
		cmp_move(CID, 0.3, -90, 0)
		wait(0.7)
		play_sound(SE_047)
		mnu_move(CID2, true, 0.3, -90, 0, EaseOutSine)
		mnu_move(CID, true, 0.3, -90, 0, EaseOutSine)
		cmp_move(CID2, 0.3, -90, 0)
		cmp_move(CID, 0.3, -90, 0)
	wait(0.7)

References
-------------
* :ref:`c_face`
* :ref:`mnu_move`
* :ref:`cmp_move`
* :ref:`wait`
* :ref:`CHARA_SET_0`
* :ref:`chara_pos`
* :ref:`play_sound`
* :ref:`mnu`
* :ref:`cmp`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "Pull_in",
	    "args": [
	        "eye1",
	        "lip1",
	        "CID",
	        "int",
	        "eye2",
	        "lip2",
	        "CID2",
	        "int2",
	        "front"
	    ],
	    "commandList": [
	        {
	            "row": 5576,
	            "command": "c_face",
	            "args": [
	                "eye1",
	                "lip1",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5577,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "120",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5578,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "120",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5579,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5580,
	            "command": "CHARA_SET_0",
	            "args": [
	                "eye2",
	                "lip2",
	                "R",
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5581,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "360",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5582,
	            "command": "play_sound",
	            "args": [
	                "SE_047"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5583,
	            "command": "if",
	            "args": [
	                "front",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5584,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-90",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5585,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.3",
	                "-90",
	                "0",
	                "EaseOutSine",
	                "0.3",
	                "1.0",
	                "1.0",
	                "EaseOutSine",
	                "0.3",
	                "0",
	                "EaseOutSine",
	                "0.3",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5586,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "-90",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5587,
	            "command": "cmp",
	            "args": [
	                "CID2",
	                "0.3",
	                "-90",
	                "0",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5588,
	            "command": "wait",
	            "args": [
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5589,
	            "command": "play_sound",
	            "args": [
	                "SE_047"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5590,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-90",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5591,
	            "command": "mnu_move",
	            "args": [
	                "CID2",
	                "true",
	                "0.3",
	                "-90",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5592,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "-90",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5593,
	            "command": "cmp_move",
	            "args": [
	                "CID2",
	                "0.3",
	                "-90",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5594,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5595,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.3",
	                "-90",
	                "0",
	                "EaseOutSine",
	                "0.3",
	                "1.0",
	                "1.0",
	                "EaseOutSine",
	                "0.3",
	                "0",
	                "EaseOutSine",
	                "0.3",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5596,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-90",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5597,
	            "command": "cmp",
	            "args": [
	                "CID2",
	                "0.3",
	                "-90",
	                "0",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5598,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "-90",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5599,
	            "command": "wait",
	            "args": [
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5600,
	            "command": "play_sound",
	            "args": [
	                "SE_047"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5601,
	            "command": "mnu_move",
	            "args": [
	                "CID2",
	                "true",
	                "0.3",
	                "-90",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5602,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-90",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5603,
	            "command": "cmp_move",
	            "args": [
	                "CID2",
	                "0.3",
	                "-90",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5604,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "-90",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5605,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5606,
	            "command": "wait",
	            "args": [
	                "0.7"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
