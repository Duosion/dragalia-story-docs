.. _c_zigzag_v_l:

c_zigzag_v_l
========================

.. code-block:: text

	c_zigzag_v_l(CID)


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
	    "name": "c_zigzag_v_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5040,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.5",
	                "-15",
	                "16",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5041,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-15",
	                "-32",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5042,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-20",
	                "16",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5043,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.5",
	                "-50",
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
