.. _JUMP_OUT_DEF:

JUMP_OUT_DEF
========================

.. code-block:: text

	JUMP_OUT_DEF(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "JUMP_OUT_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2813,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "-70",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2814,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.2",
	                "0",
	                "-70"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2815,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2816,
	            "command": "play_sound",
	            "args": [
	                "SE_082"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2817,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2818,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2819,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "200",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2820,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2821,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2822,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`NO_EMO`
* :ref:`RESET_TEXT`
* :ref:`chara_fadeout`
* :ref:`RestartAll`
