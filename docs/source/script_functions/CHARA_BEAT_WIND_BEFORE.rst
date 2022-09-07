.. _CHARA_BEAT_WIND_BEFORE:

CHARA_BEAT_WIND_BEFORE
========================

.. code-block:: text

	CHARA_BEAT_WIND_BEFORE(eye, lip, CID, int)


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
	    "name": "CHARA_BEAT_WIND_BEFORE",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 3847,
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
	            "row": 3848,
	            "command": "CHARA_BEAT_WIND_BEFORE_IN",
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
* :ref:`CHARA_SET`
* :ref:`CHARA_BEAT_WIND_BEFORE_IN`
