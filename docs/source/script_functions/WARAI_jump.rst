.. _WARAI_jump:

WARAI_jump
========================

.. code-block:: text

	WARAI_jump(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def WARAI_jump(CID):
		NO_EMO(CID)
		WARAI_EMO(CID)
		c_jump(CID)

References
-------------
* :ref:`NO_EMO`
* :ref:`WARAI_EMO`
* :ref:`c_jump`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "WARAI_jump",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4402,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4403,
	            "command": "WARAI_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4404,
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
