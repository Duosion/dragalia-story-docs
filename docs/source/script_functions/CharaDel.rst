.. _CharaDel:

CharaDel
========================

.. code-block:: text

	CharaDel(style, CID, CID2, CID3)


Arguments
------------

* style
* CID
* CID2
* CID3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	if style == "KAMITE":
		CharaOut(0.4, WAIT, 120, 0, CID, CID2, CID3)
	elif style == "SHIMOTE":
		CharaOut(0.4, WAIT, -120, 0, CID, CID2, CID3)
	elif style == "TOP":
		CharaOut(0.4, WAIT, 0, 120, CID, CID2, CID3)
	elif style == "BOTTOM":
		CharaOut(0.4, WAIT, 0, -120, CID, CID2, CID3)
	elif style == "KAMITE_REVERSE":
		CharaOut(0.4, REVERSE, 120, 0, CID, CID2, CID3)
	elif style == "SHIMOTE_REVERSE":
		CharaOut(0.4, REVERSE, -120, 0, CID, CID2, CID3)
	elif style == "TOP_REVERSE":
		CharaOut(0.4, REVERSE, 0, 120, CID, CID2, CID3)
	elif style == "BOTTOM_REVERSE":
		CharaOut(0.4, REVERSE, 0, -120, CID, CID2, CID3)
	elif style == "KAMITE_SYNC":
		CharaOut(0.4, SYNC, 120, 0, CID, CID2, CID3)
	elif style == "SHIMOTE_SYNC":
		CharaOut(0.4, SYNC, -120, 0, CID, CID2, CID3)
	elif style == "TOP_SYNC":
		CharaOut(0.4, SYNC, 0, 120, CID, CID2, CID3)
	elif style == "BOTTOM_SYNC":
		CharaOut(0.4, SYNC, 0, -120, CID, CID2, CID3)
	else:
		CharaOut(0.3, SYNC, 0, 0, CID, CID2, CID3)

References
-------------
* :ref:`CharaOut`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CharaDel",
	    "args": [
	        "style",
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 5959,
	            "command": "if",
	            "args": [
	                "style",
	                "KAMITE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5960,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "WAIT",
	                "120",
	                "0",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5961,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5962,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "WAIT",
	                "-120",
	                "0",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5963,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5964,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "WAIT",
	                "0",
	                "120",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5965,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5966,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "WAIT",
	                "0",
	                "-120",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5967,
	            "command": "elif",
	            "args": [
	                "style",
	                "KAMITE_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5968,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "REVERSE",
	                "120",
	                "0",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5969,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5970,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "REVERSE",
	                "-120",
	                "0",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5971,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5972,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "REVERSE",
	                "0",
	                "120",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5973,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5974,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "REVERSE",
	                "0",
	                "-120",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5975,
	            "command": "elif",
	            "args": [
	                "style",
	                "KAMITE_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5976,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "SYNC",
	                "120",
	                "0",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5977,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5978,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "SYNC",
	                "-120",
	                "0",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5979,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5980,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "SYNC",
	                "0",
	                "120",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5981,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5982,
	            "command": "CharaOut",
	            "args": [
	                "0.4",
	                "SYNC",
	                "0",
	                "-120",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5983,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5984,
	            "command": "CharaOut",
	            "args": [
	                "0.3",
	                "SYNC",
	                "0",
	                "0",
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5985,
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
