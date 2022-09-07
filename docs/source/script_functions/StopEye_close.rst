.. _StopEye_close:

StopEye_close
========================

.. code-block:: text

	StopEye_close(CID)


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
	    "name": "StopEye_close",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5168,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID",
	                "-2"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`chara_eyeblink`
