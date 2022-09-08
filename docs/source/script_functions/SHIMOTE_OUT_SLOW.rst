.. _SHIMOTE_OUT_SLOW:

SHIMOTE_OUT_SLOW
========================

.. code-block:: text

	SHIMOTE_OUT_SLOW(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SHIMOTE_OUT_SLOW(CID):
		NO_EMO(CID)
		RESET_TEXT()
		mnu_move(CID, true, 0.8, -120, 0, EaseInSine)
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
	    "name": "SHIMOTE_OUT_SLOW",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2704,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2705,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2706,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "-120",
	                "0",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2707,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2708,
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
