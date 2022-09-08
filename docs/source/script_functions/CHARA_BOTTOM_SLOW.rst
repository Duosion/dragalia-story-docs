.. _CHARA_BOTTOM_SLOW:

CHARA_BOTTOM_SLOW
========================

.. code-block:: text

	CHARA_BOTTOM_SLOW(eye, lip, POS, CID, int)


Arguments
------------

* eye
* lip
* POS
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	c_set_def(eye, lip, POS, CID, int)
	BOTTOM_IN_SLOW(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`BOTTOM_IN_SLOW`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BOTTOM_SLOW",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1783,
	            "command": "c_set_def",
	            "args": [
	                "eye",
	                "lip",
	                "POS",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1784,
	            "command": "BOTTOM_IN_SLOW",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
