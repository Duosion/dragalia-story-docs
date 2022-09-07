.. _ODOROKI_EMO:

ODOROKI_EMO
========================

.. code-block:: text

	ODOROKI_EMO(CID)


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
	    "name": "ODOROKI_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4427,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4428,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "5",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4429,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0005"
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
