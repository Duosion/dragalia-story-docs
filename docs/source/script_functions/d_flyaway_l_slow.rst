.. _d_flyaway_l_slow:

d_flyaway_l_slow
========================

.. code-block:: text

	d_flyaway_l_slow(CID)


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
	    "name": "d_flyaway_l_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2843,
	            "command": "play_sound",
	            "args": [
	                "SE_041"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2844,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-20",
	                "50",
	                "EaseInQuad"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2845,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-10",
	                "-25",
	                "EaseOutQuad"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2846,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "-160",
	                "275",
	                "EaseInQuad"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2847,
	            "command": "wait",
	            "args": [
	                "1.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2848,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.3"
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
