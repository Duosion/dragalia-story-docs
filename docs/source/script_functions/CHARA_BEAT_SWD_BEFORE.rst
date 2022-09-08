.. _CHARA_BEAT_SWD_BEFORE:

CHARA_BEAT_SWD_BEFORE
========================

.. code-block:: text

	CHARA_BEAT_SWD_BEFORE(eye, lip, CID, int)


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

.. code-block:: python

	def CHARA_BEAT_SWD_BEFORE(eye, lip, CID, int):
		CHARA_SET(eye, lip, C, CID, int)
		CHARA_BEAT_SWD_BEFORE_IN(CID)

References
-------------
* :ref:`CHARA_SET`
* :ref:`CHARA_BEAT_SWD_BEFORE_IN`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_SWD_BEFORE",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 3808,
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
	            "row": 3809,
	            "command": "CHARA_BEAT_SWD_BEFORE_IN",
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
