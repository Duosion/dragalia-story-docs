.. _CHARA_SHIMOTE_SLOW:

CHARA_SHIMOTE_SLOW
========================

.. code-block:: text

	CHARA_SHIMOTE_SLOW(eye, lip, POS, CID, int)


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

.. code-block:: json

	{
	    "name": "CHARA_SHIMOTE_SLOW",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1758,
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
	            "row": 1759,
	            "command": "SHIMOTE_IN_SLOW",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`c_set_def`
* :ref:`SHIMOTE_IN_SLOW`
