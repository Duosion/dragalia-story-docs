.. _c_zigzag_h_b:

c_zigzag_h_b
========================

.. code-block:: text

	c_zigzag_h_b(CID)


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
	    "name": "c_zigzag_h_b",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5019,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.5",
	                "16",
	                "-15",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5020,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-32",
	                "-15",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5021,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "16",
	                "-20",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5022,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.5",
	                "0",
	                "-50"
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
