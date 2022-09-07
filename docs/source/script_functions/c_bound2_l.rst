.. _c_bound2_l:

c_bound2_l
========================

.. code-block:: text

	c_bound2_l(CID)


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
	    "name": "c_bound2_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4780,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.25",
	                "-16",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4781,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "16",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4782,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "-16",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4783,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "16",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4784,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.0",
	                "0",
	                "0"
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
* :ref:`mnu_move`
* :ref:`cmp_move`
