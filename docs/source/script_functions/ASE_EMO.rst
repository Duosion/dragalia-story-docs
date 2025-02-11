.. _ASE_EMO:

ASE_EMO
========================

.. code-block:: text

	ASE_EMO(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def ASE_EMO(CID):
		NO_EMO(CID)
		CHARA_EMO(CID, 1, 0)
		play_sound(SE_IN_EMOTION_0001)

References
-------------
* :ref:`NO_EMO`
* :ref:`CHARA_EMO`
* :ref:`play_sound`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "ASE_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4387,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4388,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "1",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4389,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0001"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
