.. _c_avoid_r:

c_avoid_r
========================

.. code-block:: text

	c_avoid_r(CID)


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
	    "name": "c_avoid_r",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4711,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "200",
	                "-50",
	                "EaseOutBack"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4712,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "200",
	                "-50"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4713,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4714,
	            "command": "play_sound",
	            "args": [
	                "SE_046"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4715,
	            "command": "wait",
	            "args": [
	                "0.1"
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
