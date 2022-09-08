.. _CHARA_KAMITE_VERYFAST:

CHARA_KAMITE_VERYFAST
========================

.. code-block:: text

	CHARA_KAMITE_VERYFAST(eye, lip, POS, CID, int)


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
	KAMITE_IN_VERYFAST(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`KAMITE_IN_VERYFAST`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_KAMITE_VERYFAST",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1748,
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
	            "row": 1749,
	            "command": "KAMITE_IN_VERYFAST",
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
