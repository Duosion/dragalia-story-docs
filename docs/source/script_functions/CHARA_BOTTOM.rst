.. _CHARA_BOTTOM:

CHARA_BOTTOM
========================

.. code-block:: text

	CHARA_BOTTOM(eye, lip, POS, CID, int)


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

	def CHARA_BOTTOM(eye, lip, POS, CID, int):
		c_set_def(eye, lip, POS, CID, int)
		BOTTOM_IN_DEF(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`BOTTOM_IN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BOTTOM",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1778,
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
	            "row": 1779,
	            "command": "BOTTOM_IN_DEF",
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
