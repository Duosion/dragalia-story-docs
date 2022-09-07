.. _HEART_EMO:

HEART_EMO
========================

.. code-block:: text

	HEART_EMO(CID)


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
	    "name": "HEART_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4467,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4468,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "10",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4469,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0010"
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
