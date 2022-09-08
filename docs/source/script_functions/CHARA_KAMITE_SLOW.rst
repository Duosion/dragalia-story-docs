.. _CHARA_KAMITE_SLOW:

CHARA_KAMITE_SLOW
========================

.. code-block:: text

	CHARA_KAMITE_SLOW(eye, lip, POS, CID, int)


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
	KAMITE_IN_SLOW(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`KAMITE_IN_SLOW`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_KAMITE_SLOW",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1738,
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
	            "row": 1739,
	            "command": "KAMITE_IN_SLOW",
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
