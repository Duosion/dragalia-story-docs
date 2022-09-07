.. _d_flyaway_r:

d_flyaway_r
========================

.. code-block:: text

	d_flyaway_r(CID)


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
	    "name": "d_flyaway_r",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2826,
	            "command": "play_sound",
	            "args": [
	                "SE_041"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2827,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "30",
	                "50",
	                "EaseOutCirc"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2828,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "10",
	                "-30",
	                "EaseInCirc"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2829,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "150",
	                "280",
	                "EaseInQuad"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2830,
	            "command": "wait",
	            "args": [
	                "0.65"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2831,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.25"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`play_sound`
* :ref:`mnu_move`
* :ref:`wait`
* :ref:`chara_fadeout`
