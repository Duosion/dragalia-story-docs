.. _TOP_OUT_DEF:

TOP_OUT_DEF
========================

.. code-block:: text

	TOP_OUT_DEF(CID)


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
	    "name": "TOP_OUT_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2720,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2721,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2722,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "0",
	                "120",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2723,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2724,
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
