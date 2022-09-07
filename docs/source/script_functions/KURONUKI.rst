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

References
-------------
* :ref:`chara_brightness`
* :ref:`wait`
