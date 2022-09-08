.. _CHARA_SET:

CHARA_SET
========================

.. code-block:: text

	CHARA_SET(eye, lip, POS, CID, int)


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

	def CHARA_SET(eye, lip, POS, CID, int):
		c_set_def(eye, lip, POS, CID, int)
		CHARA_FADEIN_DEF(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`CHARA_FADEIN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SET",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1716,
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
	            "row": 1717,
	            "command": "CHARA_FADEIN_DEF",
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
