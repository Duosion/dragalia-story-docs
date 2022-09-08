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

.. code-block:: python

	mnu(CID, true, 0.1, 0, 0, 1, 0.1, 1, 1, 1, 0.1, 0, 1, 0.1, 1, 1)
	cmp(CID, 0.1, 0, 0, 1, 1, 0, 1)

References
-------------
* :ref:`mnu`
* :ref:`cmp`

Table Implementation
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

Sample
-------------

.. code-block:: json

	{}
