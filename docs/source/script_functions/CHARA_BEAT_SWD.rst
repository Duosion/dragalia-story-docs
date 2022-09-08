.. _CHARA_BEAT_SWD:

CHARA_BEAT_SWD
========================

.. code-block:: text

	CHARA_BEAT_SWD(eye, lip, CID, int)


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

	def CHARA_BEAT_SWD(eye, lip, CID, int):
		WFOUT_SHORT()
		CHARA_BEAT_SWD_BEFORE(eye, lip, CID, int)
		wait(0.3)
		CHARA_BEAT_AFTER_0(CID)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`CHARA_BEAT_SWD_BEFORE`
* :ref:`wait`
* :ref:`CHARA_BEAT_AFTER_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_SWD",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 3677,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3678,
	            "command": "CHARA_BEAT_SWD_BEFORE",
	            "args": [
	                "eye",
	                "lip",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3679,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3680,
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
