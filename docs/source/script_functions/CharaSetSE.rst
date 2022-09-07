.. _CharaSetSE:

CharaSetSE
========================

.. code-block:: text

	CharaSetSE(style, SE, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)


Arguments
------------

* style
* SE
* CID
* face
* eye
* lip
* posX
* posY
* CID2
* face2
* eye2
* lip2
* posX2
* posY2
* CID3
* face3
* eye3
* lip3
* posX3
* posY3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CharaSetSE",
	    "args": [
	        "style",
	        "SE",
	        "CID",
	        "face",
	        "eye",
	        "lip",
	        "posX",
	        "posY",
	        "CID2",
	        "face2",
	        "eye2",
	        "lip2",
	        "posX2",
	        "posY2",
	        "CID3",
	        "face3",
	        "eye3",
	        "lip3",
	        "posX3",
	        "posY3"
	    ],
	    "commandList": [
	        {
	            "row": 5989,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5990,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5991,
	            "command": "set_volume",
	            "args": [
	                "0",
	                "0.5",
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5992,
	            "command": "if",
	            "args": [
	                "style",
	                "KAMITE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5993,
	            "command": "_CharaSet",
	            "args": [
	                "KAMITE",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5994,
	            "command": "CharaIn",
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
	            "row": 5995,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5996,
	            "command": "_CharaSet",
	            "args": [
	                "SHIMOTE",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5997,
	            "command": "CharaIn",
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
	            "row": 5998,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5999,
	            "command": "_CharaSet",
	            "args": [
	                "TOP",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6000,
	            "command": "CharaIn",
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
	            "row": 6001,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6002,
	            "command": "_CharaSet",
	            "args": [
	                "BOTTOM",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6003,
	            "command": "CharaIn",
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
	            "row": 6004,
	            "command": "elif",
	            "args": [
	                "style",
	                "KAMITE_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6005,
	            "command": "_CharaSet",
	            "args": [
	                "KAMITE",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6006,
	            "command": "CharaIn",
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
	            "row": 6007,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6008,
	            "command": "_CharaSet",
	            "args": [
	                "SHIMOTE",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6009,
	            "command": "CharaIn",
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
	            "row": 6010,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6011,
	            "command": "_CharaSet",
	            "args": [
	                "TOP",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6012,
	            "command": "CharaIn",
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
	            "row": 6013,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6014,
	            "command": "_CharaSet",
	            "args": [
	                "BOTTOM",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6015,
	            "command": "CharaIn",
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
	            "row": 6016,
	            "command": "elif",
	            "args": [
	                "style",
	                "KAMITE_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6017,
	            "command": "_CharaSet",
	            "args": [
	                "KAMITE",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6018,
	            "command": "CharaIn",
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
	            "row": 6019,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6020,
	            "command": "_CharaSet",
	            "args": [
	                "SHIMOTE",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6021,
	            "command": "CharaIn",
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
	            "row": 6022,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6023,
	            "command": "_CharaSet",
	            "args": [
	                "TOP",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6024,
	            "command": "CharaIn",
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
	            "row": 6025,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6026,
	            "command": "_CharaSet",
	            "args": [
	                "BOTTOM",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6027,
	            "command": "CharaIn",
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
	            "row": 6028,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 6029,
	            "command": "_CharaSet",
	            "args": [
	                "style",
	                "CID",
	                "face",
	                "eye",
	                "lip",
	                "posX",
	                "posY",
	                "CID2",
	                "face2",
	                "eye2",
	                "lip2",
	                "posX2",
	                "posY2",
	                "CID3",
	                "face3",
	                "eye3",
	                "lip3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6030,
	            "command": "CharaIn",
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
	            "row": 6031,
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

References
-------------
* :ref:`play_sound`
* :ref:`wait`
* :ref:`set_volume`
* :ref:`_CharaSet`
* :ref:`CharaIn`
