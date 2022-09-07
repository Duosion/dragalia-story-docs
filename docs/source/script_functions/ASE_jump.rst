.. _ASE_jump:

ASE_jump
========================

.. code-block:: text

	ASE_jump(CID)


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
	    "name": "ASE_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4392,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4393,
	            "command": "ASE_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4394,
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
* :ref:`ASE_EMO`
* :ref:`c_jump`
