.. __CharaSet:

_CharaSet
========================

.. code-block:: text

	_CharaSet(style, CID, face, eye, lip, posX, posY, CID2, face2, eye2, lip2, posX2, posY2, CID3, face3, eye3, lip3, posX3, posY3)


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

.. code-block:: json

	{
	    "name": "_CharaSet",
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
	            "row": 5691,
	            "command": "if",
	            "args": [
	                "style",
	                "KAMITE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5692,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5693,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "posX",
	                "posY"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5694,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5695,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "120",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5696,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5697,
	            "command": "if",
	            "args": [
	                "posY",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5698,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5699,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5700,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5701,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5702,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "face"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5703,
	            "command": "eyeblink",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5704,
	            "command": "lipsynch",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5705,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5706,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5707,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5708,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "posX2",
	                "posY2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5709,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5710,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "120",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5711,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5712,
	            "command": "if",
	            "args": [
	                "posY2",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5713,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5714,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5715,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5716,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5717,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "face2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5718,
	            "command": "eyeblink",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5719,
	            "command": "lipsynch",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5720,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5721,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5722,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5723,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5724,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5725,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5726,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0.01",
	                "120",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5727,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5728,
	            "command": "if",
	            "args": [
	                "posY3",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5729,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5730,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0",
	                "0.01",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5731,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5732,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5733,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "face3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5734,
	            "command": "eyeblink",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5735,
	            "command": "lipsynch",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5736,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5737,
	            "command": "elif",
	            "args": [
	                "style",
	                "SHIMOTE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5738,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5739,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "posX",
	                "posY"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5740,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "-120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5741,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "-120",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5742,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5743,
	            "command": "if",
	            "args": [
	                "posY",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5744,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5745,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5746,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5747,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5748,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "face"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5749,
	            "command": "eyeblink",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5750,
	            "command": "lipsynch",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5751,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5752,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5753,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5754,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "posX2",
	                "posY2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5755,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "-120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5756,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "-120",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5757,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5758,
	            "command": "if",
	            "args": [
	                "posY2",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5759,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5760,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5761,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5762,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5763,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "face2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5764,
	            "command": "eyeblink",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5765,
	            "command": "lipsynch",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5766,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5767,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5768,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5769,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5770,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5771,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "-120",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5772,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0.01",
	                "-120",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5773,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5774,
	            "command": "if",
	            "args": [
	                "posY3",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5775,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5776,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5777,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5778,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5779,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "face3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5780,
	            "command": "eyeblink",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5781,
	            "command": "lipsynch",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5782,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5783,
	            "command": "elif",
	            "args": [
	                "style",
	                "TOP"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5784,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5785,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "posX",
	                "posY"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5786,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0",
	                "120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5787,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "0",
	                "120"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5788,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5789,
	            "command": "if",
	            "args": [
	                "posY",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5790,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5791,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5792,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5793,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5794,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "face"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5795,
	            "command": "eyeblink",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5796,
	            "command": "lipsynch",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5797,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5798,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5799,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5800,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "posX2",
	                "posY2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5801,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "0",
	                "120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5802,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "0",
	                "120"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5803,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5804,
	            "command": "if",
	            "args": [
	                "posY2",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5805,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5806,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5807,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5808,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5809,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "face2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5810,
	            "command": "eyeblink",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5811,
	            "command": "lipsynch",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5812,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5813,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5814,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5815,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5816,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5817,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "0",
	                "120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5818,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0.01",
	                "0",
	                "120"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5819,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5820,
	            "command": "if",
	            "args": [
	                "posY3",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5821,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5822,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5823,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5824,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5825,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "face3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5826,
	            "command": "eyeblink",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5827,
	            "command": "lipsynch",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5828,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5829,
	            "command": "elif",
	            "args": [
	                "style",
	                "BOTTOM"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5830,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5831,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "posX",
	                "posY"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5832,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0",
	                "-120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5833,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "0",
	                "-120"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5834,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5835,
	            "command": "if",
	            "args": [
	                "posY",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5836,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5837,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5838,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5839,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5840,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "face"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5841,
	            "command": "eyeblink",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5842,
	            "command": "lipsynch",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5843,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5844,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5845,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5846,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "posX2",
	                "posY2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5847,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "0",
	                "-120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5848,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "0",
	                "-120"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5849,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5850,
	            "command": "if",
	            "args": [
	                "posY2",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5851,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5852,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5853,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5854,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5855,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "face2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5856,
	            "command": "eyeblink",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5857,
	            "command": "lipsynch",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5858,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5859,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5860,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5861,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5862,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5863,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "0",
	                "-120",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5864,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0.01",
	                "0",
	                "-120"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5865,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5866,
	            "command": "if",
	            "args": [
	                "posY3",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5867,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5868,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5869,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5870,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5871,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "face3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5872,
	            "command": "eyeblink",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5873,
	            "command": "lipsynch",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5874,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5875,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5876,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5877,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "posX",
	                "posY"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5878,
	            "command": "if",
	            "args": [
	                "posY",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5879,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5880,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5881,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5882,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5883,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "face"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5884,
	            "command": "eyeblink",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5885,
	            "command": "lipsynch",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5886,
	            "command": "if",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5887,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5888,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5889,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "posX2",
	                "posY2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5890,
	            "command": "if",
	            "args": [
	                "posY2",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5891,
	            "command": "chara_act_manual",
	            "args": [
	                "CID2",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5892,
	            "command": "chara_act_complete",
	            "args": [
	                "CID2",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5893,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5894,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5895,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "face2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5896,
	            "command": "eyeblink",
	            "args": [
	                "CID2",
	                "eye2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5897,
	            "command": "lipsynch",
	            "args": [
	                "CID2",
	                "lip2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5898,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5899,
	            "command": "if",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5900,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5901,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5902,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "posX3",
	                "posY3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5903,
	            "command": "if",
	            "args": [
	                "posY3",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5904,
	            "command": "chara_act_manual",
	            "args": [
	                "CID3",
	                "true",
	                "0.01",
	                "0",
	                "-2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5905,
	            "command": "chara_act_complete",
	            "args": [
	                "CID3",
	                "0.01",
	                "0",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5906,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5907,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5908,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "face3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5909,
	            "command": "eyeblink",
	            "args": [
	                "CID3",
	                "eye3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5910,
	            "command": "lipsynch",
	            "args": [
	                "CID3",
	                "lip3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5911,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5912,
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
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`chara_act_manual`
* :ref:`chara_act_complete`
* :ref:`wait`
* :ref:`chara_face`
* :ref:`eyeblink`
* :ref:`lipsynch`
