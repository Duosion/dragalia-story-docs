.. _ODOROKI_jump:

ODOROKI_jump
========================

.. code-block:: text

	ODOROKI_jump(CID)


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
	    "name": "ODOROKI_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4432,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4433,
	            "command": "ODOROKI_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4434,
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
* :ref:`ODOROKI_EMO`
* :ref:`c_jump`
