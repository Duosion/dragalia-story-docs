.. _HIRAMEKI_EMO:

HIRAMEKI_EMO
========================

.. code-block:: text

	HIRAMEKI_EMO(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def HIRAMEKI_EMO(CID):
		NO_EMO(CID)
		CHARA_EMO(CID, 9, 0)
		play_sound(SE_IN_EMOTION_0009)

References
-------------
* :ref:`NO_EMO`
* :ref:`CHARA_EMO`
* :ref:`play_sound`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "HIRAMEKI_EMO",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4457,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4458,
	            "command": "CHARA_EMO",
	            "args": [
	                "CID",
	                "9",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4459,
	            "command": "play_sound",
	            "args": [
	                "SE_IN_EMOTION_0009"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
