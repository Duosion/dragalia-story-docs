.. _IKARI_EMO:

IKARI_EMO
========================

.. code-block:: text

	IKARI_EMO(CID)


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
	    "name": "IKARI_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4417,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4418,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "4",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4419,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0004"
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
