.. _StopLip_close:

StopLip_close
========================

.. code-block:: text

	StopLip_close(CID)


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
	    "name": "StopLip_close",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5178,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID",
	                "-1"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`chara_lipsynch`
