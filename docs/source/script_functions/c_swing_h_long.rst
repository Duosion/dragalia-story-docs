.. _c_swing_h_long:

c_swing_h_long
========================

.. code-block:: text

	c_swing_h_long(CID)


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
	    "name": "c_swing_h_long",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4845,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "50",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4846,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "-100",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4847,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "50",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4848,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.6",
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
