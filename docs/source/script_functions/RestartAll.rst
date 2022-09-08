.. _RestartAll:

RestartAll
========================

.. code-block:: text

	RestartAll(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	RestartEye(CID)
	RestartLip(CID)

References
-------------
* :ref:`RestartEye`
* :ref:`RestartLip`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "RestartAll",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5192,
	            "command": "RestartEye",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5193,
	            "command": "RestartLip",
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
