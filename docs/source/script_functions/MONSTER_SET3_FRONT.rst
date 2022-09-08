.. _MONSTER_SET3_FRONT:

MONSTER_SET3_FRONT
========================

.. code-block:: text

	MONSTER_SET3_FRONT(IN, CID, CID2, CID3)


Arguments
------------

* IN
* CID
* CID2
* CID3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_SET3_FRONT(IN, CID, CID2, CID3):
		chara_visible(CID, false)
		chara_visible(CID2, false)
		chara_visible(CID3, false)
		chara_pos(CID, 200, 0)
		chara_pos(CID2, -200, 0)
		chara_pos(CID3, 0, 50)
		chara_face(CID, 12)
		chara_face(CID2, 12)
		chara_face(CID3, 12)
		mnu_scale(CID3, true, 0.01, 1.0, 1.0, EaseOutCubic)
		mnu_scale(CID2, true, 0.01, 0.7, 0.7, EaseOutCubic)
		mnu_scale(CID, true, 0.01, 0.7, 0.7, EaseOutCubic)
		cmp_scale(CID3, 0.01, 1.0, 1.0)
		cmp_scale(CID2, 0.01, 0.7, 0.7)
		cmp_scale(CID, 0.01, 0.7, 0.7)
		wait(0.01)
		if IN == "KAMITE":
			KAMITE_IN_DEF(CID)
			KAMITE_IN_DEF(CID2)
			wait(0.2)
			mnu(CID3, true, 0.05, 120, 0, 1, 0.05, 1, 1, 1, 0.05, 0, 1, 0.05, 0, 1)
			mnu(CID3, false, 0.4, -120, 0, EaseOutSine, 0.4, 1, 1, 1, 0.4, 0, 1, 0.4, 1, EaseOutSine)
			cmp(CID3, 0.45, 0, 0, 1, 1, 0, 1)
			NO_EMO(CID)
			NO_EMO(CID2)
			wait(0.45)
		elif IN == "SHIMOTE":
			SHIMOTE_IN_DEF(CID)
			SHIMOTE_IN_DEF(CID2)
			wait(0.2)
			mnu(CID3, true, 0.05, -120, 0, 1, 0.05, 1, 1, 1, 0.05, 0, 1, 0.05, 0, 1)
			mnu(CID3, false, 0.4, 120, 0, EaseOutSine, 0.4, 1, 1, 1, 0.4, 0, 1, 0.4, 1, EaseOutSine)
			cmp(CID3, 0.45, 0, 0, 1, 1, 0, 1)
			NO_EMO(CID)
			NO_EMO(CID2)
			wait(0.45)
		else:
			mnu_fade(CID3, true, 0.4, 1.0, 1)
			mnu_fade(CID, true, 0.4, 1.0, 1)
			mnu_fade(CID2, true, 0.4, 1.0, 1)
			cmp_fade(CID3, 0.4, 1.0)
			cmp_fade(CID, 0.4, 1.0)
			cmp_fade(CID2, 0.4, 1.0)
			wait(0.4)

References
-------------
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`chara_face`
* :ref:`mnu_scale`
* :ref:`cmp_scale`
* :ref:`wait`
* :ref:`KAMITE_IN_DEF`
* :ref:`mnu`
* :ref:`cmp`
* :ref:`NO_EMO`
* :ref:`SHIMOTE_IN_DEF`
* :ref:`mnu_fade`
* :ref:`cmp_fade`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_SET3_FRONT",
	    "args": [
	        "IN",
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 5528,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5529,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5530,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5531,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "200",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5532,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "-200",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5533,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "0",
	                "50"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5534,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "12"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5535,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "12"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5536,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "12"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5537,
	            "command": "mnu_scale",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "1.0",
	                "1.0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5538,
	            "command": "mnu_scale",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "0.7",
	                "0.7",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5539,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0.7",
	                "0.7",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5540,
	            "command": "cmp_scale",
	            "args": [
	                "CID3",
	                "0.01",
	                "1.0",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5541,
	            "command": "cmp_scale",
	            "args": [
	                "CID2",
	                "0.01",
	                "0.7",
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5542,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.01",
	                "0.7",
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5543,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5544,
	            "command": "if",
	            "args": [
	                "IN",
	                "KAMITE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5545,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5546,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5547,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5548,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "0.05",
	                "120",
	                "0",
	                "1",
	                "0.05",
	                "1",
	                "1",
	                "1",
	                "0.05",
	                "0",
	                "1",
	                "0.05",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5549,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "false",
	                "0.4",
	                "-120",
	                "0",
	                "EaseOutSine",
	                "0.4",
	                "1",
	                "1",
	                "1",
	                "0.4",
	                "0",
	                "1",
	                "0.4",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5550,
	            "command": "cmp",
	            "args": [
	                "CID3",
	                "0.45",
	                "0",
	                "0",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5551,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5552,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5553,
	            "command": "wait",
	            "args": [
	                "0.45"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5554,
	            "command": "elif",
	            "args": [
	                "IN",
	                "SHIMOTE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5555,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5556,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5557,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5558,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "0.05",
	                "-120",
	                "0",
	                "1",
	                "0.05",
	                "1",
	                "1",
	                "1",
	                "0.05",
	                "0",
	                "1",
	                "0.05",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5559,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "false",
	                "0.4",
	                "120",
	                "0",
	                "EaseOutSine",
	                "0.4",
	                "1",
	                "1",
	                "1",
	                "0.4",
	                "0",
	                "1",
	                "0.4",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5560,
	            "command": "cmp",
	            "args": [
	                "CID3",
	                "0.45",
	                "0",
	                "0",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5561,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5562,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5563,
	            "command": "wait",
	            "args": [
	                "0.45"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5564,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5565,
	            "command": "mnu_fade",
	            "args": [
	                "CID3",
	                "true",
	                "0.4",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5566,
	            "command": "mnu_fade",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5567,
	            "command": "mnu_fade",
	            "args": [
	                "CID2",
	                "true",
	                "0.4",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5568,
	            "command": "cmp_fade",
	            "args": [
	                "CID3",
	                "0.4",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5569,
	            "command": "cmp_fade",
	            "args": [
	                "CID",
	                "0.4",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5570,
	            "command": "cmp_fade",
	            "args": [
	                "CID2",
	                "0.4",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5571,
	            "command": "wait",
	            "args": [
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5572,
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
