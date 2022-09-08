.. _CharaSet:

CharaSet
========================

.. code-block:: text

	CharaSet(style, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)


Arguments
------------

* style
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

.. code-block:: python

	if style == KAMITE:
		_CharaSet(KAMITE, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, WAIT, -120, 0, CID, CID2, CID3)
	elif style == SHIMOTE:
		_CharaSet(SHIMOTE, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, WAIT, 120, 0, CID, CID2, CID3)
	elif style == TOP:
		_CharaSet(TOP, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, WAIT, 0, -120, CID, CID2, CID3)
	elif style == BOTTOM:
		_CharaSet(BOTTOM, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, WAIT, 0, 120, CID, CID2, CID3)
	elif style == KAMITE_REVERSE:
		_CharaSet(KAMITE, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, REVERSE, -120, 0, CID, CID2, CID3)
	elif style == SHIMOTE_REVERSE:
		_CharaSet(SHIMOTE, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, REVERSE, 120, 0, CID, CID2, CID3)
	elif style == TOP_REVERSE:
		_CharaSet(TOP, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, REVERSE, 0, -120, CID, CID2, CID3)
	elif style == BOTTOM_REVERSE:
		_CharaSet(BOTTOM, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, REVERSE, 0, 120, CID, CID2, CID3)
	elif style == KAMITE_SYNC:
		_CharaSet(KAMITE, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, SYNC, -120, 0, CID, CID2, CID3)
	elif style == SHIMOTE_SYNC:
		_CharaSet(SHIMOTE, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, SYNC, 120, 0, CID, CID2, CID3)
	elif style == TOP_SYNC:
		_CharaSet(TOP, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, SYNC, 0, -120, CID, CID2, CID3)
	elif style == BOTTOM_SYNC:
		_CharaSet(BOTTOM, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.4, SYNC, 0, 120, CID, CID2, CID3)
	else:
		_CharaSet(style, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)
		CharaIn(0.3, SYNC, 0, 0, CID, CID2, CID3)

References
-------------
* :ref:`_CharaSet`
* :ref:`CharaIn`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CharaSet",
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
	    "commandList": [
	        {
	            "row": 5916,
	            "command": "if",
	            "args": [
	                "style",
	                "KAMITE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5917,
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
	            "row": 5918,
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
	            "row": 5919,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5920,
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
	            "row": 5921,
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
	            "row": 5922,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5923,
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
	            "row": 5924,
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
	            "row": 5925,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5926,
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
	            "row": 5927,
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
	            "row": 5928,
	            "command": "elif",
	            "args": [
	                "style",
	                "KAMITE_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5929,
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
	            "row": 5930,
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
	            "row": 5931,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5932,
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
	            "row": 5933,
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
	            "row": 5934,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5935,
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
	            "row": 5936,
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
	            "row": 5937,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM_REVERSE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5938,
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
	            "row": 5939,
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
	            "row": 5940,
	            "command": "elif",
	            "args": [
	                "style",
	                "KAMITE_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5941,
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
	            "row": 5942,
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
	            "row": 5943,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5944,
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
	            "row": 5945,
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
	            "row": 5946,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5947,
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
	            "row": 5948,
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
	            "row": 5949,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM_SYNC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5950,
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
	            "row": 5951,
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
	            "row": 5952,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5953,
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
	            "row": 5954,
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
	            "row": 5955,
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
