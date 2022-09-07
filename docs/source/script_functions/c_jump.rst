.. _c_jump:

c_jump
========================

.. code-block:: text

	c_jump(CID)


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
	    "name": "c_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4892,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4893,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-60",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4894,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "0",
	                "14",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4895,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "0",
	                "-4",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4896,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.6",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
