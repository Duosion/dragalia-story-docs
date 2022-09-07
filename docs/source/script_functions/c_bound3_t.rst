.. _c_bound3_t:

c_bound3_t
========================

.. code-block:: text

	c_bound3_t(CID)


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
	    "name": "c_bound3_t",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4732,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.25",
	                "0",
	                "16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4733,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4734,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "24",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4735,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-24",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4736,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4737,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4738,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.5",
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
