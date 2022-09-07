.. _IKARI_jump:

IKARI_jump
========================

.. code-block:: text

	IKARI_jump(CID)


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
	    "name": "IKARI_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4422,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4423,
	            "command": "IKARI_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4424,
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
* :ref:`IKARI_EMO`
* :ref:`c_jump`
