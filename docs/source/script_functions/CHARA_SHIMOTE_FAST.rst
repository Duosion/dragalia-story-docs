.. _CHARA_SHIMOTE_FAST:

CHARA_SHIMOTE_FAST
========================

.. code-block:: text

	CHARA_SHIMOTE_FAST(eye, lip, POS, CID, int)


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
	    "name": "CHARA_SHIMOTE_FAST",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1763,
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
	            "row": 1764,
	            "command": "SHIMOTE_IN_FAST",
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
* :ref:`SHIMOTE_IN_FAST`
