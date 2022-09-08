.. _CHARA_KAMITE:

CHARA_KAMITE
========================

.. code-block:: text

	CHARA_KAMITE(eye, lip, POS, CID, int)


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
	KAMITE_IN_DEF(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`KAMITE_IN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_KAMITE",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1733,
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
	            "row": 1734,
	            "command": "KAMITE_IN_DEF",
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
