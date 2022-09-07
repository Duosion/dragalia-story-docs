.. _HEART_jump:

HEART_jump
========================

.. code-block:: text

	HEART_jump(CID)


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
	    "name": "HEART_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4472,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4473,
	            "command": "HEART_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4474,
	            "command": "c_jump",
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
* :ref:`NO_EMO`
* :ref:`HEART_EMO`
* :ref:`c_jump`
