.. _MOYA_EMO:

MOYA_EMO
========================

.. code-block:: text

	MOYA_EMO(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	NO_EMO(CID)
	CHARA_EMO(CID, 7, 0)
	play_sound(SE_IN_EMOTION_0007)

References
-------------
* :ref:`NO_EMO`
* :ref:`CHARA_EMO`
* :ref:`play_sound`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MOYA_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4447,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4448,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "7",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4449,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0007"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
