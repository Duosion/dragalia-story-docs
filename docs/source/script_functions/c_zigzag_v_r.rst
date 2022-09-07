.. _c_zigzag_v_r:

c_zigzag_v_r
========================

.. code-block:: text

	c_zigzag_v_r(CID)


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
	    "name": "c_zigzag_v_r",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5033,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.5",
	                "15",
	                "16",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5034,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "15",
	                "-32",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5035,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "20",
	                "16",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5036,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.5",
	                "50",
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
