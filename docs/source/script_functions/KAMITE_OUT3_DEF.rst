.. _KAMITE_OUT3_DEF:

KAMITE_OUT3_DEF
========================

.. code-block:: text

	KAMITE_OUT3_DEF(CID, CID2, CID3)


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

	def KAMITE_OUT3_DEF(CID, CID2, CID3):
		NO_EMO(CID)
		NO_EMO(CID2)
		NO_EMO(CID3)
		mnu(CID, true, 0.4, 120, 0, EaseInSine, 0.4, 1, 1, 0, 0.4, 0, 0, 0.4, 0, 1)
		mnu(CID2, true, 0.4, 120, 0, EaseInSine, 0.4, 1, 1, 0, 0.4, 0, 0, 0.4, 0, 1)
		mnu(CID3, true, 0.4, 120, 0, EaseInSine, 0.4, 1, 1, 0, 0.4, 0, 0, 0.4, 0, 1)
		wait(0.4)
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
	    "name": "KAMITE_OUT3_DEF",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2936,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2937,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2938,
	            "command": "NO_EMO",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2939,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "120",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "1",
	                "0",
	                "0.4",
	                "0",
	                "0",
	                "0.4",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2940,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.4",
	                "120",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "1",
	                "0",
	                "0.4",
	                "0",
	                "0",
	                "0.4",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2941,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "0.4",
	                "120",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "1",
	                "0",
	                "0.4",
	                "0",
	                "0",
	                "0.4",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2942,
	            "command": "wait",
	            "args": [
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2943,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2944,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2945,
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
