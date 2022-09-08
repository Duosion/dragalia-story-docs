.. _KAMITE_OUT_DEF_SE:

KAMITE_OUT_DEF_SE
========================

.. code-block:: text

	KAMITE_OUT_DEF_SE(CID, SE)


Arguments
------------

* CID
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def KAMITE_OUT_DEF_SE(CID, SE):
		play_sound(SE)
		KAMITE_OUT_DEF(CID)
		wait(0.5)
		BGMTUNE_DOWN_0(SE)

References
-------------
* :ref:`play_sound`
* :ref:`KAMITE_OUT_DEF`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "KAMITE_OUT_DEF_SE",
	    "args": [
	        "CID",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2771,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2772,
	            "command": "KAMITE_OUT_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2773,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2774,
	            "command": "BGMTUNE_DOWN_0",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
