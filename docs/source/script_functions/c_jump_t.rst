.. _c_jump_t:

c_jump_t
========================

.. code-block:: text

	c_jump_t(CID)


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
	    "name": "c_jump_t",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4948,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "100",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4949,
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
	            "row": 4950,
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
	            "row": 4951,
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
	            "row": 4952,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.0",
	                "0",
	                "50"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
