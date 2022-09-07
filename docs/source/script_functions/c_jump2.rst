.. _c_jump2:

c_jump2
========================

.. code-block:: text

	c_jump2(CID)


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
	    "name": "c_jump2",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4900,
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
	            "row": 4901,
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
	            "row": 4902,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "60",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4903,
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
	            "row": 4904,
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
	            "row": 4905,
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
	            "row": 4906,
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
