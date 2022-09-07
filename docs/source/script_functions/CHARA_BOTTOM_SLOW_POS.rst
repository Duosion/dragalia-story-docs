.. _CHARA_BOTTOM_SLOW_POS:

CHARA_BOTTOM_SLOW_POS
========================

.. code-block:: text

	CHARA_BOTTOM_SLOW_POS(eye, lip, X, Y, CID, int)


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
	    "name": "CHARA_BOTTOM_SLOW_POS",
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
	            "row": 1850,
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
	            "row": 1851,
	            "command": "BOTTOM_IN_SLOW",
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

References
-------------
* :ref:`CHARA_SET_POS_0`
* :ref:`BOTTOM_IN_SLOW`
