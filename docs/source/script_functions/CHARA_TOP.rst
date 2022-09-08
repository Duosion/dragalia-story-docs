.. _CHARA_TOP:

CHARA_TOP
========================

.. code-block:: text

	CHARA_TOP(eye, lip, POS, CID, int)


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

	def CHARA_TOP(eye, lip, POS, CID, int):
		c_set_def(eye, lip, POS, CID, int)
		TOP_IN_DEF(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`TOP_IN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_TOP",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1773,
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
	            "row": 1774,
	            "command": "TOP_IN_DEF",
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
