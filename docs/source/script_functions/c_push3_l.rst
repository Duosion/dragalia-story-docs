.. _c_push3_l:

c_push3_l
========================

.. code-block:: text

	c_push3_l(CID)


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
	    "name": "c_push3_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4641,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-50",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4642,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4643,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "-30",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4644,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4645,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "-15",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4646,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.6",
	                "-95",
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
