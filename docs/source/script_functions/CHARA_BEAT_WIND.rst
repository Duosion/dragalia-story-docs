.. _CHARA_BEAT_WIND:

CHARA_BEAT_WIND
========================

.. code-block:: text

	CHARA_BEAT_WIND(eye, lip, CID, int)


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
	    "name": "CHARA_BEAT_WIND",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 3684,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3685,
	            "command": "CHARA_BEAT_WIND_BEFORE",
	            "args": [
	                "eye",
	                "lip",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3686,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3687,
	            "command": "CHARA_BEAT_AFTER_0",
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
* :ref:`WFOUT_SHORT`
* :ref:`CHARA_BEAT_WIND_BEFORE`
* :ref:`wait`
* :ref:`CHARA_BEAT_AFTER_0`
