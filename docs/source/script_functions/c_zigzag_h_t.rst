.. _c_zigzag_h_t:

c_zigzag_h_t
========================

.. code-block:: text

	c_zigzag_h_t(CID)


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
	    "name": "c_zigzag_h_t",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5026,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.5",
	                "16",
	                "15",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5027,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-32",
	                "15",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5028,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "16",
	                "20",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5029,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.5",
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
