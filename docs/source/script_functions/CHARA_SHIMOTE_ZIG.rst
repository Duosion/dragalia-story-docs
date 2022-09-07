.. _CHARA_SHIMOTE_ZIG:

CHARA_SHIMOTE_ZIG
========================

.. code-block:: text

	CHARA_SHIMOTE_ZIG(eye, lip, POS, CID, int)


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
	    "name": "CHARA_SHIMOTE_ZIG",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1793,
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
	            "row": 1794,
	            "command": "SHIMOTE_IN_ZIG",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1795,
	            "command": "wait",
	            "args": [
	                "0.7"
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
* :ref:`c_set_def`
* :ref:`SHIMOTE_IN_ZIG`
* :ref:`wait`
