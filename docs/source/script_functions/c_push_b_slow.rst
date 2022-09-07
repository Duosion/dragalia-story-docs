.. _c_push_b_slow:

c_push_b_slow
========================

.. code-block:: text

	c_push_b_slow(CID)


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
	    "name": "c_push_b_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4616,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "0",
	                "-50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4617,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.4",
	                "0",
	                "-50"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
