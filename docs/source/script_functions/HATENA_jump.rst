.. _HATENA_jump:

HATENA_jump
========================

.. code-block:: text

	HATENA_jump(CID)


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
	    "name": "HATENA_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4442,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4443,
	            "command": "HATENA_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4444,
	            "command": "c_jump",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`NO_EMO`
* :ref:`HATENA_EMO`
* :ref:`c_jump`
