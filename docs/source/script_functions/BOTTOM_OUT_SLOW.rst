.. _BOTTOM_OUT_SLOW:

BOTTOM_OUT_SLOW
========================

.. code-block:: text

	BOTTOM_OUT_SLOW(CID)


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
	    "name": "BOTTOM_OUT_SLOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2744,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2745,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2746,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "0",
	                "-120",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2747,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2748,
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
