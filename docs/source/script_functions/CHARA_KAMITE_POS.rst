.. _CHARA_KAMITE_POS:

CHARA_KAMITE_POS
========================

.. code-block:: text

	CHARA_KAMITE_POS(eye, lip, X, Y, CID, int)


Arguments
------------

* eye
* lip
* X
* Y
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_KAMITE_POS(eye, lip, X, Y, CID, int):
		CHARA_SET_POS_0(eye, lip, X, Y, CID, int)
		KAMITE_IN_DEF(CID)

References
-------------
* :ref:`CHARA_SET_POS_0`
* :ref:`KAMITE_IN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_KAMITE_POS",
	    "args": [
	        "eye",
	        "lip",
	        "X",
	        "Y",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1830,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "eye",
	                "lip",
	                "X",
	                "Y",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1831,
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
