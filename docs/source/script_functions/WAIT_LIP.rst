.. _WAIT_LIP:

WAIT_LIP
========================

.. code-block:: text

	WAIT_LIP(CID, sec)


Arguments
------------

* CID
* sec

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "WAIT_LIP",
	    "args": [
	        "CID",
	        "sec"
	    ],
	    "commandList": [
	        {
	            "row": 5186,
	            "command": "StopLip_close",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5187,
	            "command": "wait",
	            "args": [
	                "sec"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5188,
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

References
-------------
* :ref:`StopLip_close`
* :ref:`wait`
* :ref:`RestartLip`
