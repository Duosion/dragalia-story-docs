.. _KAMITE_OUT3_SLOW:

KAMITE_OUT3_SLOW
========================

.. code-block:: text

	KAMITE_OUT3_SLOW(CID, CID2, CID3)


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
	mnu(CID, true, 0.8, 120, 0, EaseInSine, 0.8, 1, 1, 0, 0.8, 0, 0, 0.8, 0, 1)
	mnu(CID2, true, 0.8, 120, 0, EaseInSine, 0.8, 1, 1, 0, 0.8, 0, 0, 0.8, 0, 1)
	mnu(CID3, true, 0.8, 120, 0, EaseInSine, 0.8, 1, 1, 0, 0.8, 0, 0, 0.8, 0, 1)
	wait(0.8)
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
	    "name": "KAMITE_OUT3_SLOW",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2949,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2950,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2951,
	            "command": "NO_EMO",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2952,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "120",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "1",
	                "1",
	                "0",
	                "0.8",
	                "0",
	                "0",
	                "0.8",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2953,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.8",
	                "120",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "1",
	                "1",
	                "0",
	                "0.8",
	                "0",
	                "0",
	                "0.8",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2954,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "0.8",
	                "120",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "1",
	                "1",
	                "0",
	                "0.8",
	                "0",
	                "0",
	                "0.8",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2955,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2956,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2957,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2958,
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
