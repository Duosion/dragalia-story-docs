.. _c_mnu_reset:

c_mnu_reset
========================

.. code-block:: text

	c_mnu_reset(CID)


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
	    "name": "c_mnu_reset",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5014,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0",
	                "0",
	                "0",
	                "1",
	                "0",
	                "1",
	                "1",
	                "1",
	                "0",
	                "0",
	                "1",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5015,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "0",
	                "0",
	                "0",
	                "1",
	                "1",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu`
* :ref:`cmp`
