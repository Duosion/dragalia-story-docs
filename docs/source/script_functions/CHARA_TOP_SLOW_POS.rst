.. _CHARA_TOP_SLOW_POS:

CHARA_TOP_SLOW_POS
========================

.. code-block:: text

	CHARA_TOP_SLOW_POS(eye, lip, X, Y, CID, int)


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
	    "name": "CHARA_TOP_SLOW_POS",
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
	            "row": 1845,
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
	            "row": 1846,
	            "command": "TOP_IN_SLOW",
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
* :ref:`TOP_IN_SLOW`
