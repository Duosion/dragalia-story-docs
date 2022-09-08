.. _SHIMOTE_OUT3_FAST:

SHIMOTE_OUT3_FAST
========================

.. code-block:: text

	SHIMOTE_OUT3_FAST(CID, CID2, CID3)


Arguments
------------

* CID
* CID2
* CID3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SHIMOTE_OUT3_FAST(CID, CID2, CID3):
		NO_EMO(CID)
		NO_EMO(CID2)
		NO_EMO(CID3)
		mnu(CID, true, 0.3, -120, 0, EaseInSine, 0.3, 1, 1, 0, 0.3, 0, 0, 0.3, 0, 1)
		mnu(CID2, true, 0.3, -120, 0, EaseInSine, 0.3, 1, 1, 0, 0.3, 0, 0, 0.3, 0, 1)
		mnu(CID3, true, 0.3, -120, 0, EaseInSine, 0.3, 1, 1, 0, 0.3, 0, 0, 0.3, 0, 1)
		wait(0.3)
		chara_visible(CID, false)
		chara_visible(CID2, false)
		chara_visible(CID3, false)

References
-------------
* :ref:`NO_EMO`
* :ref:`mnu`
* :ref:`wait`
* :ref:`chara_visible`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHIMOTE_OUT3_FAST",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 3001,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3002,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3003,
	            "command": "NO_EMO",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3004,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.3",
	                "1",
	                "1",
	                "0",
	                "0.3",
	                "0",
	                "0",
	                "0.3",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3005,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.3",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.3",
	                "1",
	                "1",
	                "0",
	                "0.3",
	                "0",
	                "0",
	                "0.3",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3006,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "0.3",
	                "-120",
	                "0",
	                "EaseInSine",
	                "0.3",
	                "1",
	                "1",
	                "0",
	                "0.3",
	                "0",
	                "0",
	                "0.3",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3007,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3008,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3009,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3010,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
