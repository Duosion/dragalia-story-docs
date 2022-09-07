.. _c_mnu_def:

c_mnu_def
========================

.. code-block:: text

	c_mnu_def(CID)


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
	    "name": "c_mnu_def",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5009,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.1",
	                "0",
	                "0",
	                "1",
	                "0.1",
	                "1",
	                "1",
	                "1",
	                "0.1",
	                "0",
	                "1",
	                "0.1",
	                "1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5010,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "0.1",
	                "0",
	                "0",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu`
* :ref:`cmp`
