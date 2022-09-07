.. _KAMITE_OUT_FAST:

KAMITE_OUT_FAST
========================

.. code-block:: text

	KAMITE_OUT_FAST(CID)


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
	    "name": "KAMITE_OUT_FAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2688,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2689,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2690,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "120",
	                "0",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2691,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2692,
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
