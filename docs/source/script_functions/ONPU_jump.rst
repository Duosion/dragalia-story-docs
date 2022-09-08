.. _ONPU_jump:

ONPU_jump
========================

.. code-block:: text

	ONPU_jump(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def ONPU_jump(CID):
		NO_EMO(CID)
		ONPU_EMO(CID)
		c_jump(CID)

References
-------------
* :ref:`NO_EMO`
* :ref:`ONPU_EMO`
* :ref:`c_jump`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "ONPU_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4412,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4413,
	            "command": "ONPU_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4414,
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
