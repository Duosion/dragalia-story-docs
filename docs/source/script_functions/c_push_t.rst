.. _c_push_t:

c_push_t
========================

.. code-block:: text

	c_push_t(CID)


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
	    "name": "c_push_t",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4601,
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
	            "row": 4602,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.2",
	                "0",
	                "50"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
