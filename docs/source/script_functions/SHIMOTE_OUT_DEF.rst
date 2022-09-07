.. _SHIMOTE_OUT_DEF:

SHIMOTE_OUT_DEF
========================

.. code-block:: text

	SHIMOTE_OUT_DEF(CID)


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
	    "name": "SHIMOTE_OUT_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2696,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2697,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2698,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "-120",
	                "0",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2699,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2700,
	            "command": "RestartAll",
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
* :ref:`NO_EMO`
* :ref:`RESET_TEXT`
* :ref:`mnu_move`
* :ref:`chara_fadeout`
* :ref:`RestartAll`
