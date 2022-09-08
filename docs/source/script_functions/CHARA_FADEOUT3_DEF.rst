.. _CHARA_FADEOUT3_DEF:

CHARA_FADEOUT3_DEF
========================

.. code-block:: text

	CHARA_FADEOUT3_DEF(CID, CID2, CID3)


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

	NO_EMO(CID)
	NO_EMO(CID2)
	NO_EMO(CID3)
	RESET_TEXT()
	mnu_fade(CID, true, 0.2, 0, 1)
	mnu_fade(CID2, true, 0.2, 0, 1)
	mnu_fade(CID3, true, 0.2, 0, 1)
	wait(0.2)
	chara_visible(CID, false)
	chara_visible(CID2, false)
	chara_visible(CID3, false)
	RestartAll(CID)
	RestartAll(CID2)
	RestartAll(CID3)

References
-------------
* :ref:`NO_EMO`
* :ref:`RESET_TEXT`
* :ref:`mnu_fade`
* :ref:`wait`
* :ref:`chara_visible`
* :ref:`RestartAll`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_FADEOUT3_DEF",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2646,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2647,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2648,
	            "command": "NO_EMO",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2649,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2650,
	            "command": "mnu_fade",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2651,
	            "command": "mnu_fade",
	            "args": [
	                "CID2",
	                "true",
	                "0.2",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2652,
	            "command": "mnu_fade",
	            "args": [
	                "CID3",
	                "true",
	                "0.2",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2653,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2654,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2655,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2656,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2657,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2658,
	            "command": "RestartAll",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2659,
	            "command": "RestartAll",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
