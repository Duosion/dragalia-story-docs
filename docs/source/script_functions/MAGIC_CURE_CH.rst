.. _MAGIC_CURE_CH:

MAGIC_CURE_CH
========================

.. code-block:: text

	MAGIC_CURE_CH(eye2, lip2, CID, CID2, int)


Arguments
------------

* eye2
* lip2
* CID
* CID2
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MAGIC_CURE_CH(eye2, lip2, CID, CID2, int):
		WFOUT_DEF()
		MAGIC_CURE_BEFORE()
		CHARA_RESET(CID)
		CHARA_SET(eye2, lip2, C, CID2, int)
		MAGIC_CURE_AFTER()
		wait(0.8)

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`MAGIC_CURE_BEFORE`
* :ref:`CHARA_RESET`
* :ref:`CHARA_SET`
* :ref:`MAGIC_CURE_AFTER`
* :ref:`wait`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MAGIC_CURE_CH",
	    "args": [
	        "eye2",
	        "lip2",
	        "CID",
	        "CID2",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 4328,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4329,
	            "command": "MAGIC_CURE_BEFORE",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4330,
	            "command": "CHARA_RESET",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4331,
	            "command": "CHARA_SET",
	            "args": [
	                "eye2",
	                "lip2",
	                "C",
	                "CID2",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4332,
	            "command": "MAGIC_CURE_AFTER",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4333,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
