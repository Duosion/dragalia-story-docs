.. _KAMITE_OUT_DEF:

KAMITE_OUT_DEF
========================

.. code-block:: text

	KAMITE_OUT_DEF(CID)


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
	    "name": "KAMITE_OUT_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2672,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2673,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2674,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "120",
	                "0",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2675,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2676,
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
