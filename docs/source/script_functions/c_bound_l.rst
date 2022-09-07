.. _c_bound_l:

c_bound_l
========================

.. code-block:: text

	c_bound_l(CID)


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
	    "name": "c_bound_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4686,
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
	            "row": 4687,
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
	            "row": 4688,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.5",
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
