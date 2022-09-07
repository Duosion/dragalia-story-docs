.. _StopLip:

StopLip
========================

.. code-block:: text

	StopLip(CID)


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
	    "name": "StopLip",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5174,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID",
	                "-2"
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
