.. _c_push_t_slow:

c_push_t_slow
========================

.. code-block:: text

	c_push_t_slow(CID)


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
	    "name": "c_push_t_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4606,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "0",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4607,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.4",
	                "0",
	                "50"
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
