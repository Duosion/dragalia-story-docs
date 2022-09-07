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

References
-------------
* :ref:`chara_eyeblink`
