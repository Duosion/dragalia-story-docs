.. _c_bound2_b_slow:

c_bound2_b_slow
========================

.. code-block:: text

	c_bound2_b_slow(CID)


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
	    "name": "c_bound2_b_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4762,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.5",
	                "0",
	                "-12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4763,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4764,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "-12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4765,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4766,
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
