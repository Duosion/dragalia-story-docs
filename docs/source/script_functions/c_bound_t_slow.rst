.. _c_bound_t_slow:

c_bound_t_slow
========================

.. code-block:: text

	c_bound_t_slow(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.4, 0, 16, EaseOutCubic)
	mnu_move(CID, false, 0.4, 0, -16, EaseOutCubic)
	cmp_move(CID, 0.8, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_bound_t_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4661,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "0",
	                "16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4662,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.4",
	                "0",
	                "-16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4663,
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
