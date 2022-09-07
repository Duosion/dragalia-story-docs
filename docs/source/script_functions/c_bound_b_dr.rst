.. _c_bound_b_dr:

c_bound_b_dr
========================

.. code-block:: text

	c_bound_b_dr(CID)


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
	    "name": "c_bound_b_dr",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4679,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.7",
	                "0",
	                "-16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4680,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4681,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "0",
	                "16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4682,
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

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
