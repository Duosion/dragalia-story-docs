.. _CharaOut:

CharaOut
========================

.. code-block:: text

	CharaOut(sec, wait, X, Y, CID, CID2, CID3)


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

.. code-block:: json

	{
	    "name": "CharaOut",
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
	            "row": 6138,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6139,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6140,
	            "command": "chara_emotion",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6141,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6142,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6143,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6144,
	            "command": "chara_emotion",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6145,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6146,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6147,
	            "command": "reset_text",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6148,
	            "command": "if",
	            "args": [
	                "wait",
	                "WAIT"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6149,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6150,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6151,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6152,
	            "command": "cmp",
	            "args": [
	                "CID3",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6153,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6154,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6155,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6156,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6157,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6158,
	            "command": "cmp",
	            "args": [
	                "CID2",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6159,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6160,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6161,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6162,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6163,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6164,
	            "command": "elif",
	            "args": [
	                "wait",
	                "REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6165,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6166,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6167,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6168,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6169,
	            "command": "chara_emotion",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6170,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6171,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6172,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6173,
	            "command": "chara_emotion",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6174,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6175,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6176,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6177,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6178,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6179,
	            "command": "cmp",
	            "args": [
	                "CID2",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6180,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6181,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6182,
	            "command": "chara_emotion",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6183,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6184,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6185,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6186,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6187,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6188,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6189,
	            "command": "cmp",
	            "args": [
	                "CID3",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6190,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6191,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6192,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6193,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6194,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6195,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6196,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6197,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6198,
	            "command": "cmp",
	            "args": [
	                "CID2",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6199,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6200,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6201,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6202,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "sec",
	                "X",
	                "Y",
	                "EaseInSine",
	                "sec",
	                "1",
	                "1",
	                "1",
	                "sec",
	                "0",
	                "1",
	                "sec",
	                "0",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6203,
	            "command": "cmp",
	            "args": [
	                "CID3",
	                "sec",
	                "X",
	                "Y",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6204,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6205,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6206,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6207,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6208,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6209,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6210,
	            "command": "eyeblink",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6211,
	            "command": "lipsynch",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6212,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6213,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6214,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6215,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6216,
	            "command": "eyeblink",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6217,
	            "command": "lipsynch",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6218,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6219,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6220,
	            "command": "eyeblink",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6221,
	            "command": "lipsynch",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`chara_emotion`
* :ref:`reset_text`
* :ref:`mnu`
* :ref:`cmp`
* :ref:`wait`
* :ref:`chara_visible`
* :ref:`eyeblink`
* :ref:`lipsynch`
