.. _CHARA_FADEOUT2_DEF:

CHARA_FADEOUT2_DEF
========================

.. code-block:: text

	CHARA_FADEOUT2_DEF(CID, CID2)


Arguments
------------

* CID
* CID2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_FADEOUT2_DEF",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 2634,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2635,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2636,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2637,
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
	            "row": 2638,
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
	            "row": 2639,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2640,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2641,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2642,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2643,
	            "command": "RestartAll",
	            "args": [
	                "CID2"
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
* :ref:`mnu_fade`
* :ref:`wait`
* :ref:`chara_visible`
* :ref:`RestartAll`
