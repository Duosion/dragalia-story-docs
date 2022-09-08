.. _RestartEye:

RestartEye
========================

.. code-block:: text

	RestartEye(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def RestartEye(CID):
		chara_eyeblink(CID)

References
-------------
* :ref:`chara_eyeblink`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "RestartEye",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5171,
	            "command": "chara_eyeblink",
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
