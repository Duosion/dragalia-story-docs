.. _WARP_IN:

WARP_IN
========================

.. code-block:: text

	WARP_IN(eye, lip, CID, int)


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

.. code-block:: json

	{
	    "name": "WARP_IN",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 2024,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2025,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2026,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2027,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2028,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2029,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2030,
	            "command": "set_render_target",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2031,
	            "command": "play_sound",
	            "args": [
	                "SE_010"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2032,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_002",
	                "EFF_SCE_2D_REN_000"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2033,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "0",
	                "25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2034,
	            "command": "wait",
	            "args": [
	                "2.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2035,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2036,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`chara_visible`
* :ref:`chara_face`
* :ref:`eye1`
* :ref:`lip1`
* :ref:`wait`
* :ref:`set_render_target`
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`NO_EFFECT`
