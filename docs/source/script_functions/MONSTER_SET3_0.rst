.. _MONSTER_SET3_0:

MONSTER_SET3_0
========================

.. code-block:: text

	MONSTER_SET3_0(CID, CID2, CID3)


Arguments
------------

* CID
* CID2
* CID3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_SET3_0(CID, CID2, CID3):
		chara_visible(CID, false)
		chara_visible(CID2, false)
		chara_visible(CID3, false)
		chara_contrast(CID, 0.73, 0)
		chara_saturation(CID, 1.77, 0)
		chara_brightness(CID, 1.02, 0)
		chara_contrast(CID2, 0.73, 0)
		chara_saturation(CID2, 1.77, 0)
		chara_brightness(CID2, 1.02, 0)
		chara_pos(CID, 200, 240)
		chara_pos(CID2, -200, 240)
		chara_pos(CID3, 0, 10)
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

References
-------------
* :ref:`chara_visible`
* :ref:`chara_contrast`
* :ref:`chara_saturation`
* :ref:`chara_brightness`
* :ref:`chara_pos`
* :ref:`chara_face`
* :ref:`mnu_scale`
* :ref:`cmp_scale`
* :ref:`wait`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_SET3_0",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2307,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2308,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2309,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2310,
	            "command": "chara_contrast",
	            "args": [
	                "CID",
	                "0.73",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2311,
	            "command": "chara_saturation",
	            "args": [
	                "CID",
	                "1.77",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2312,
	            "command": "chara_brightness",
	            "args": [
	                "CID",
	                "1.02",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2313,
	            "command": "chara_contrast",
	            "args": [
	                "CID2",
	                "0.73",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2314,
	            "command": "chara_saturation",
	            "args": [
	                "CID2",
	                "1.77",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2315,
	            "command": "chara_brightness",
	            "args": [
	                "CID2",
	                "1.02",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2316,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "200",
	                "240"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2317,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "-200",
	                "240"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2318,
	            "command": "chara_pos",
	            "args": [
	                "CID3",
	                "0",
	                "10"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2319,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "12"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2320,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "12"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2321,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "12"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2322,
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
	            "row": 2323,
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
	            "row": 2324,
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
	            "row": 2325,
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
	            "row": 2326,
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
	            "row": 2327,
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
	            "row": 2328,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
