.. _c_bound_b_slow:

c_bound_b_slow
========================

.. code-block:: text

	c_bound_b_slow(CID)


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
	    "name": "c_bound_b_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4673,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "0",
	                "-16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4674,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.4",
	                "0",
	                "16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4675,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.8",
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
