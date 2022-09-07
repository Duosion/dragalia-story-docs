.. _MONSTER_BEAT2_AFTER:

MONSTER_BEAT2_AFTER
========================

.. code-block:: text

	MONSTER_BEAT2_AFTER(CID, CID2)


Arguments
------------

* CID
* CID2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_BEAT2_AFTER",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 4210,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4211,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint",
	                "0.6",
	                "1",
	                "1",
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
	            "row": 4212,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint",
	                "0.6",
	                "1",
	                "1",
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
	            "row": 4213,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4214,
	            "command": "play_sound",
	            "args": [
	                "SE_262"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4215,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4216,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4217,
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
	            "row": 4218,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4219,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4220,
	            "command": "RestartAll",
	            "args": [
	                "CID2"
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
* :ref:`WFOUT_SHORT`
* :ref:`mnu`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`chara_visible`
* :ref:`effect_shake_bg`
* :ref:`RestartAll`
