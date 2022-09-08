.. _HIRAMEKI_jump:

HIRAMEKI_jump
========================

.. code-block:: text

	HIRAMEKI_jump(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def HIRAMEKI_jump(CID):
		NO_EMO(CID)
		HIRAMEKI_EMO(CID)
		c_jump(CID)

References
-------------
* :ref:`NO_EMO`
* :ref:`HIRAMEKI_EMO`
* :ref:`c_jump`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "HIRAMEKI_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4462,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4463,
	            "command": "HIRAMEKI_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4464,
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
