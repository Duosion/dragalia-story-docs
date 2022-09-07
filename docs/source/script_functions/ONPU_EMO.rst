.. _ONPU_EMO:

ONPU_EMO
========================

.. code-block:: text

	ONPU_EMO(CID)


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
	    "name": "ONPU_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4407,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4408,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4409,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0003"
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
