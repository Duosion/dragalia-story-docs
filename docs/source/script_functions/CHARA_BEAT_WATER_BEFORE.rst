.. _CHARA_BEAT_WATER_BEFORE:

CHARA_BEAT_WATER_BEFORE
========================

.. code-block:: text

	CHARA_BEAT_WATER_BEFORE(eye, lip, CID, int)


Arguments
------------

* eye
* lip
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_WATER_BEFORE",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 3842,
	            "command": "CHARA_SET",
	            "args": [
	                "eye",
	                "lip",
	                "C",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3843,
	            "command": "CHARA_BEAT_WATER_BEFORE_IN",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`CHARA_SET`
* :ref:`CHARA_BEAT_WATER_BEFORE_IN`
