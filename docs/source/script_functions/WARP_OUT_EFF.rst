.. _WARP_OUT_EFF:

WARP_OUT_EFF
========================

.. code-block:: text

	WARP_OUT_EFF(eye, lip, CID, int)


Arguments
------------

* eye
* lip
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	chara_face(CID, int)
	eye1(CID, eye)
	lip1(CID, lip)
	wait(0.1)
	set_render_target(CID, 0)
	WFOUT_SHORT()
	play_sound(SE_010)
	set_BG_effect(1, 1, EFF_002, EFF_SCE_2D_REN_000)
	set_BG_effect_trigger(2, 2, 0, 29)
	wait(0.2)
	chara_clear(CID)
	wait(2.5)
	set_BG_effect(1, 1, 0, 0)

References
-------------
* :ref:`chara_face`
* :ref:`eye1`
* :ref:`lip1`
* :ref:`wait`
* :ref:`set_render_target`
* :ref:`WFOUT_SHORT`
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`chara_clear`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "WARP_OUT_EFF",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 2056,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2057,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2058,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2059,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2060,
	            "command": "set_render_target",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2061,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2062,
	            "command": "play_sound",
	            "args": [
	                "SE_010"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2063,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_002",
	                "EFF_SCE_2D_REN_000"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2064,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "0",
	                "29"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2065,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2066,
	            "command": "chara_clear",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2067,
	            "command": "wait",
	            "args": [
	                "2.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2068,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
