.. _NO_EMO:

NO_EMO
========================

.. code-block:: text

	NO_EMO(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def NO_EMO(CID):
		chara_emotion(CID, 0)

References
-------------
* :ref:`chara_emotion`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "NO_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4477,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
