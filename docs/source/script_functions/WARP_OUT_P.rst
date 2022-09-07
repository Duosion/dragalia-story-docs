.. _WARP_OUT_P:

WARP_OUT_P
========================

.. code-block:: text

	WARP_OUT_P(eye, lip, CID, int)


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
	    "name": "WARP_OUT_P",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 2008,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2009,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2010,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2011,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2012,
	            "command": "set_render_target",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2013,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2014,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_PROLOGUE_0001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2015,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_002",
	                "EFF_SCE_2D_REN_000"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2016,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "0",
	                "29"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2017,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2018,
	            "command": "chara_clear",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2019,
	            "command": "wait",
	            "args": [
	                "2.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2020,
	            "command": "NO_EFFECT",
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
* :ref:`NO_EFFECT`
