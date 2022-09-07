.. _CHARA_TYPE:

CHARA_TYPE
========================

.. code-block:: text

	CHARA_TYPE(CID, eye2, lip2, POS2, CID2, int2)


Arguments
------------

* CID
* eye2
* lip2
* POS2
* CID2
* int2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_TYPE",
	    "args": [
	        "CID",
	        "eye2",
	        "lip2",
	        "POS2",
	        "CID2",
	        "int2"
	    ],
	    "commandList": [
	        {
	            "row": 1721,
	            "command": "chara_clear",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1722,
	            "command": "c_set_def",
	            "args": [
	                "eye2",
	                "lip2",
	                "POS2",
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1723,
	            "command": "chara_fadein",
	            "args": [
	                "CID2",
	                "0.4"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`chara_clear`
* :ref:`c_set_def`
* :ref:`chara_fadein`
