.. _HATENA_EMO:

HATENA_EMO
========================

.. code-block:: text

	HATENA_EMO(CID)


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
	    "name": "HATENA_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4437,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4438,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "6",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4439,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0006"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`NO_EMO`
* :ref:`CHARA_EMO`
* :ref:`play_sound`
