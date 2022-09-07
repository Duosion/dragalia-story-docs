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

References
-------------
* :ref:`RestartEye`
* :ref:`RestartLip`
