.. _SHIMOTE_OUT_FAST:

SHIMOTE_OUT_FAST
========================

.. code-block:: text

	SHIMOTE_OUT_FAST(CID)


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
	    "name": "SHIMOTE_OUT_FAST",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2712,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2713,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2714,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-120",
	                "0",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2715,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2716,
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
