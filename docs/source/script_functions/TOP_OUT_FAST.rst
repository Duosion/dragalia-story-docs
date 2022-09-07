.. _TOP_OUT_FAST:

TOP_OUT_FAST
========================

.. code-block:: text

	TOP_OUT_FAST(CID)


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
	    "name": "TOP_OUT_FAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2752,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2753,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2754,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "0",
	                "120",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2755,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2756,
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
