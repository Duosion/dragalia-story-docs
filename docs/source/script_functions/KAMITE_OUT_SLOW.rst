.. _KAMITE_OUT_SLOW:

KAMITE_OUT_SLOW
========================

.. code-block:: text

	KAMITE_OUT_SLOW(CID)


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
	    "name": "KAMITE_OUT_SLOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2680,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2681,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2682,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "120",
	                "0",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2683,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2684,
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
