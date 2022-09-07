.. _WARAI_EMO:

WARAI_EMO
========================

.. code-block:: text

	WARAI_EMO(CID)


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
	    "name": "WARAI_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4397,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4398,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4399,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0002"
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
* :ref:`CHARA_EMO`
* :ref:`play_sound`
