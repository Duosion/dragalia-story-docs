.. _RestartLip:

RestartLip
========================

.. code-block:: text

	RestartLip(CID)


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
	    "name": "RestartLip",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5182,
	            "command": "chara_lipsynch",
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
* :ref:`chara_lipsynch`
