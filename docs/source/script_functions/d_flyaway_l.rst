.. _d_flyaway_l:

d_flyaway_l
========================

.. code-block:: text

	d_flyaway_l(CID)


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
	    "name": "d_flyaway_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2835,
	            "command": "play_sound",
	            "args": [
	                "SE_041"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2836,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.1",
	                "-30",
	                "50",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2837,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.4",
	                "-160",
	                "250",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2838,
	            "command": "wait",
	            "args": [
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2839,
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
