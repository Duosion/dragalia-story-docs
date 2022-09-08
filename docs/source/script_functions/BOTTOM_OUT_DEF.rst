.. _BOTTOM_OUT_DEF:

BOTTOM_OUT_DEF
========================

.. code-block:: text

	BOTTOM_OUT_DEF(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def BOTTOM_OUT_DEF(CID):
		NO_EMO(CID)
		RESET_TEXT()
		mnu_move(CID, true, 0.4, 0, -120, EaseInSine)
		chara_fadeout(CID, 0.4)
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
	    "name": "BOTTOM_OUT_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2728,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2729,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2730,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "0",
	                "-120",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2731,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2732,
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
