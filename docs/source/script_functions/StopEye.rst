.. _StopEye:

StopEye
========================

.. code-block:: text

	StopEye(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def StopEye(CID):
		chara_eyeblink(CID, -1)

References
-------------
* :ref:`chara_eyeblink`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "StopEye",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5164,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID",
	                "-1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
