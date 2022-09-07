.. _c_swing2_h_slow:

c_swing2_h_slow
========================

.. code-block:: text

	c_swing2_h_slow(CID)


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
	    "name": "c_swing2_h_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4828,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.5",
	                "16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4829,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-32",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4830,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "32",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4831,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4832,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "2.0",
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
