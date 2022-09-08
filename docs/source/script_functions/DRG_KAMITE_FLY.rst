.. _DRG_KAMITE_FLY:

DRG_KAMITE_FLY
========================

.. code-block:: text

	DRG_KAMITE_FLY(eye, lip, CID)


Arguments
------------

* eye
* lip
* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	VIS(CID, POS_CENTER)
	chara_face(CID, 1)
	eye1(CID, eye)
	lip1(CID, lip)
	play_sound(SE_040)
	mnu_move(CID, true, 0.01, 190, 200, 1)
	mnu_move(CID, false, 0.6, -190, -210, EaseOutCirc)
	mnu_move(CID, false, 0.6, 0, 0, 1)
	mnu_move(CID, false, 0.2, 0, 10, EaseInSine)
	wait(0.01)
	chara_fadein(CID, 0.25)
	wait(0.35)
	play_sound(SE_133)
	effect_shake_bg(12, 0.2, 0.6, 1)
	SEFOUT_DEF()

References
-------------
* :ref:`VIS`
* :ref:`chara_face`
* :ref:`eye1`
* :ref:`lip1`
* :ref:`play_sound`
* :ref:`mnu_move`
* :ref:`wait`
* :ref:`chara_fadein`
* :ref:`effect_shake_bg`
* :ref:`SEFOUT_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "DRG_KAMITE_FLY",
	    "args": [
	        "eye",
	        "lip",
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 1945,
	            "command": "VIS",
	            "args": [
	                "CID",
	                "POS_CENTER"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1946,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1947,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1948,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1949,
	            "command": "play_sound",
	            "args": [
	                "SE_040"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1950,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "190",
	                "200",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1951,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "-190",
	                "-210",
	                "EaseOutCirc"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1952,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1953,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "10",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1954,
	            "command": "wait",
	            "args": [
	                "0.01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1955,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1956,
	            "command": "wait",
	            "args": [
	                "0.35"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1957,
	            "command": "play_sound",
	            "args": [
	                "SE_133"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1958,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.2",
	                "0.6",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1959,
	            "command": "SEFOUT_DEF",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
