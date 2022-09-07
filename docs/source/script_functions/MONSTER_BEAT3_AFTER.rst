.. _MONSTER_BEAT3_AFTER:

MONSTER_BEAT3_AFTER
========================

.. code-block:: text

	MONSTER_BEAT3_AFTER(CID, CID2, CID3)


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

.. code-block:: json

	{
	    "name": "MONSTER_BEAT3_AFTER",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 4224,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4225,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint",
	                "0.6",
	                "0.7",
	                "0.7",
	                "1",
	                "0.6",
	                "0",
	                "1",
	                "0.6",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4226,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint",
	                "0.6",
	                "0.7",
	                "0.7",
	                "1",
	                "0.6",
	                "0",
	                "1",
	                "0.6",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4227,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint",
	                "0.6",
	                "1.0",
	                "1.0",
	                "1",
	                "0.6",
	                "0",
	                "1",
	                "0.6",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4228,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4229,
	            "command": "play_sound",
	            "args": [
	                "SE_262"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4230,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4231,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4232,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4233,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.1",
	                "0.2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4234,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4235,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4236,
	            "command": "RestartAll",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4237,
	            "command": "RestartAll",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`mnu`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`chara_visible`
* :ref:`effect_shake_bg`
* :ref:`RestartAll`
