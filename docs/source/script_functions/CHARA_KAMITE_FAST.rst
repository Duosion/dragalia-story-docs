.. _CHARA_KAMITE_FAST:

CHARA_KAMITE_FAST
========================

.. code-block:: text

	CHARA_KAMITE_FAST(eye, lip, POS, CID, int)


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

	def CHARA_KAMITE_FAST(eye, lip, POS, CID, int):
		c_set_def(eye, lip, POS, CID, int)
		KAMITE_IN_FAST(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`KAMITE_IN_FAST`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_KAMITE_FAST",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1743,
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
	            "row": 1744,
	            "command": "KAMITE_IN_FAST",
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
