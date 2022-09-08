.. _CHARA_SHIMOTE:

CHARA_SHIMOTE
========================

.. code-block:: text

	CHARA_SHIMOTE(eye, lip, POS, CID, int)


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

	def CHARA_SHIMOTE(eye, lip, POS, CID, int):
		c_set_def(eye, lip, POS, CID, int)
		SHIMOTE_IN_DEF(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`SHIMOTE_IN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SHIMOTE",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1753,
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
	            "row": 1754,
	            "command": "SHIMOTE_IN_DEF",
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
