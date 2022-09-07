.. _CharaDelSE:

CharaDelSE
========================

.. code-block:: text

	CharaDelSE(style, SE, CID, CID2, CID3)


Arguments
------------

* style
* SE
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
	    "name": "CharaDelSE",
	    "args": [
	        "style",
	        "SE",
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 6034,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6035,
	            "command": "if",
	            "args": [
	                "style",
	                "KAMITE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6036,
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
	            "row": 6037,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6038,
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
	            "row": 6039,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6040,
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
	            "row": 6041,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6042,
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
	            "row": 6043,
	            "command": "elif",
	            "args": [
	                "style",
	                "KAMITE_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6044,
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
	            "row": 6045,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6046,
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
	            "row": 6047,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6048,
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
	            "row": 6049,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6050,
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
	            "row": 6051,
	            "command": "elif",
	            "args": [
	                "style",
	                "KAMITE_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6052,
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
	            "row": 6053,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6054,
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
	            "row": 6055,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6056,
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
	            "row": 6057,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6058,
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
	            "row": 6059,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6060,
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
	            "row": 6061,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6062,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6063,
	            "command": "set_volume",
	            "args": [
	                "0",
	                "0.5",
	                "SE"
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
* :ref:`play_sound`
* :ref:`CharaOut`
* :ref:`wait`
* :ref:`set_volume`
