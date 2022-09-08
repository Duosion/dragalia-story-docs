.. _TOP_OUT_SLOW:

TOP_OUT_SLOW
========================

.. code-block:: text

	TOP_OUT_SLOW(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	NO_EMO(CID)
	RESET_TEXT()
	mnu_move(CID, true, 0.8, 0, 120, EaseInSine)
	chara_fadeout(CID, 0.8)
	RestartAll(CID)

References
-------------
* :ref:`NO_EMO`
* :ref:`RESET_TEXT`
* :ref:`mnu_move`
* :ref:`chara_fadeout`
* :ref:`RestartAll`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "TOP_OUT_SLOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2736,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2737,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2738,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "0",
	                "120",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2739,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2740,
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
