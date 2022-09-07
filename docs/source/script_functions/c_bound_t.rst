.. _c_bound_t:

c_bound_t
========================

.. code-block:: text

	c_bound_t(CID)


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
	    "name": "c_bound_t",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4655,
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
	            "row": 4656,
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
	            "row": 4657,
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
