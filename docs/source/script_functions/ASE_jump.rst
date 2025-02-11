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

.. code-block:: python

	def ASE_jump(CID):
		NO_EMO(CID)
		ASE_EMO(CID)
		c_jump(CID)

References
-------------
* :ref:`NO_EMO`
* :ref:`ASE_EMO`
* :ref:`c_jump`

Table Implementation
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

Sample
-------------

.. code-block:: json

	{}
