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

References
-------------
* :ref:`CHARA_SET_POS_0`
* :ref:`KAMITE_IN_DEF`
