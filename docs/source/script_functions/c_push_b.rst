.. _c_push_b:

c_push_b
========================

.. code-block:: text

	c_push_b(CID)


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
	    "name": "c_push_b",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4611,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "-50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4612,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.2",
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
