.. _KURONUKI:

KURONUKI
========================

.. code-block:: text

	KURONUKI(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def KURONUKI(CID):
		chara_brightness(CID, 0)
		wait(0)

References
-------------
* :ref:`chara_brightness`
* :ref:`wait`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "KURONUKI",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4502,
	            "command": "chara_brightness",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4503,
	            "command": "wait",
	            "args": [
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
