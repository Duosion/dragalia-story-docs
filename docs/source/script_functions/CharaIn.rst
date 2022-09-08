.. _CharaIn:

CharaIn
========================

.. code-block:: text

	CharaIn(sec, wait, X, Y, CID, CID2, CID3)


Arguments
------------

* sec
* wait
* X
* Y
* CID
* CID2
* CID3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	if wait == WAIT:
		mnu(CID, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
		cmp(CID, sec, X, Y, 1, 1, 0, 1)
		wait(sec)
	if CID2 == 0:
	else:
		mnu(CID2, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
		cmp(CID2, sec, X, Y, 1, 1, 0, 1)
		wait(sec)
	if CID3 == 0:
	else:
		mnu(CID3, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
		cmp(CID3, sec, X, Y, 1, 1, 0, 1)
		wait(sec)
	elif wait == REVERSE:
	if CID3 == 0:
	else:
		mnu(CID3, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
		cmp(CID3, sec, X, Y, 1, 1, 0, 1)
		wait(sec)
	if CID2 == 0:
	else:
		mnu(CID2, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
		cmp(CID2, sec, X, Y, 1, 1, 0, 1)
	if CID3 == 0:
	else:
		chara_emotion(CID3, 0)
	wait(sec)
	mnu(CID, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
	cmp(CID, sec, X, Y, 1, 1, 0, 1)
	if CID2 == 0:
	else:
		chara_emotion(CID2, 0)
	if CID3 == 0:
	else:
		chara_emotion(CID3, 0)
	wait(sec)
	else:
		mnu(CID, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
		cmp(CID, sec, X, Y, 1, 1, 0, 1)
	if CID2 == 0:
	else:
		mnu(CID2, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
		cmp(CID2, sec, X, Y, 1, 1, 0, 1)
	if CID3 == 0:
	else:
		mnu(CID3, true, sec, X, Y, EaseOutSine, sec, 1, 1, 1, sec, 0, 1, sec, 1, EaseOutSine)
		cmp(CID3, sec, X, Y, 1, 1, 0, 1)
	wait(sec)
	chara_visible(CID, true)
	if CID2 == 0:
	else:
		chara_visible(CID2, true)
	if CID3 == 0:
	else:
		chara_visible(CID3, true)

References
-------------
* :ref:`mnu`
* :ref:`cmp`
* :ref:`wait`
* :ref:`chara_emotion`
* :ref:`chara_visible`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CharaIn",
	    "args": [
	        "sec",
	        "wait",
	        "X",
	        "Y",
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 6067,
	            "command": "if",
	            "args": [
	                "wait",
	                "WAIT"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6068,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6069,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6070,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6071,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6072,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6073,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6074,
	            "command": "cmp",
	            "args": [
	                "CID2",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6075,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6076,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6077,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6078,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6079,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6080,
	            "command": "cmp",
	            "args": [
	                "CID3",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6081,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6082,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6083,
	            "command": "elif",
	            "args": [
	                "wait",
	                "REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6084,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6085,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6086,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6087,
	            "command": "cmp",
	            "args": [
	                "CID3",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6088,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6089,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6090,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6091,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6092,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6093,
	            "command": "cmp",
	            "args": [
	                "CID2",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6094,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6095,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6096,
	            "command": "chara_emotion",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6097,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6098,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6099,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6100,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6101,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6102,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6103,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6104,
	            "command": "chara_emotion",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6105,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6106,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6107,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6108,
	            "command": "chara_emotion",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6109,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6110,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6111,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6112,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6113,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6114,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6115,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6116,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6117,
	            "command": "cmp",
	            "args": [
	                "CID2",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6118,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6119,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6120,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6121,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseOutSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6122,
	            "command": "cmp",
	            "args": [
	                "CID3",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6123,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6124,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6125,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6126,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6127,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6128,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6129,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6130,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6131,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6132,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6133,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6134,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
