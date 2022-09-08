.. _WARP_OUT:

WARP_OUT
========================

.. code-block:: text

	WARP_OUT(eye, lip, CID, int)


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

	def WARP_OUT(eye, lip, CID, int):
		chara_face(CID, int)
		eye1(CID, eye)
		lip1(CID, lip)
		wait(0.1)
		set_render_target(CID, 0)
		WFOUT_SHORT()
		play_sound(SE_010)
		set_BG_effect(EFF_002, EFF_SCE_2D_REN_000)
		set_BG_effect_trigger(0, 29)
		wait(0.2)
		chara_clear(CID)
		wait(2.5)
		NO_EFFECT()

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

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "WARP_OUT",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 2040,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2041,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2042,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2043,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2044,
	            "command": "set_render_target",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2045,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2046,
	            "command": "play_sound",
	            "args": [
	                "SE_010"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2047,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_002",
	                "EFF_SCE_2D_REN_000"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2048,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "0",
	                "29"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2049,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2050,
	            "command": "chara_clear",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2051,
	            "command": "wait",
	            "args": [
	                "2.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2052,
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
