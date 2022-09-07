.. _BOTTOM_OUT_FAST:

BOTTOM_OUT_FAST
========================

.. code-block:: text

	BOTTOM_OUT_FAST(CID)


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
	    "name": "BOTTOM_OUT_FAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2760,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2761,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2762,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "0",
	                "-120",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2763,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2764,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`NO_EMO`
* :ref:`RESET_TEXT`
* :ref:`mnu_move`
* :ref:`chara_fadeout`
* :ref:`RestartAll`
