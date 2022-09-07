.. _WARP_IN_P:

WARP_IN_P
========================

.. code-block:: text

	WARP_IN_P(eye, lip, CID, int)


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
	    "name": "WARP_IN_P",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1992,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1993,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1994,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1995,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1996,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1997,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1998,
	            "command": "set_render_target",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1999,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_PROLOGUE_0001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2000,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_002",
	                "EFF_SCE_2D_REN_000"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2001,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "0",
	                "25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2002,
	            "command": "wait",
	            "args": [
	                "2.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2003,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2004,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
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
