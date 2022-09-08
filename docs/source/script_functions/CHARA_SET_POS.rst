.. _CHARA_SET_POS:

CHARA_SET_POS
========================

.. code-block:: text

	CHARA_SET_POS(eye, lip, X, Y, CID, int)


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

	CHARA_SET_POS_0(eye, lip, X, Y, CID, int)
	CHARA_FADEIN_DEF(CID)

References
-------------
* :ref:`CHARA_SET_POS_0`
* :ref:`CHARA_FADEIN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SET_POS",
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
	            "row": 1825,
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
	            "row": 1826,
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
