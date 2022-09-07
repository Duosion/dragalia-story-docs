.. _c_falldown_r:

c_falldown_r
========================

.. code-block:: text

	c_falldown_r(CID, X, Y, SE)


Arguments
------------

* CID
* X
* Y
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "c_falldown_r",
	    "args": [
	        "CID",
	        "X",
	        "Y",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 5067,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "40",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5068,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "40",
	                "-260",
	                "EaseInCubic",
	                "0.2",
	                "1",
	                "1",
	                "1",
	                "0.2",
	                "-30",
	                "1",
	                "0.2",
	                "1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5069,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "20",
	                "14",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5070,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "20",
	                "-4",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5071,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "0.6",
	                "120",
	                "-200",
	                "1",
	                "1",
	                "-30",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5072,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5073,
	            "command": "play_sound",
	            "args": [
	                "SE_065"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5074,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5075,
	            "command": "StopEye_close",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5076,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5077,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5078,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5079,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5080,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.2",
	                "1.0"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`mnu`
* :ref:`cmp`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`StopEye_close`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`effect_shake_bg`
