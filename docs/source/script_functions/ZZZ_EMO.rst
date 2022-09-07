.. _ZZZ_EMO:

ZZZ_EMO
========================

.. code-block:: text

	ZZZ_EMO(CID)


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
	    "name": "ZZZ_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4452,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4453,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "8",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4454,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0008"
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
