.. _c_push_l:

c_push_l
========================

.. code-block:: text

	c_push_l(CID)


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
	    "name": "c_push_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4621,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "-50",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4622,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.2",
	                "-50",
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
