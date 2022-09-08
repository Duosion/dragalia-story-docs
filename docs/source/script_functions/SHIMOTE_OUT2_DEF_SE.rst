.. _SHIMOTE_OUT2_DEF_SE:

SHIMOTE_OUT2_DEF_SE
========================

.. code-block:: text

	SHIMOTE_OUT2_DEF_SE(CID, CID2, SE)


Arguments
------------

* CID
* CID2
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SHIMOTE_OUT2_DEF_SE(CID, CID2, SE):
		play_sound(SE)
		SHIMOTE_OUT2_DEF(CID, CID2)
		wait(0.5)
		BGMTUNE_DOWN_0(SE)

References
-------------
* :ref:`play_sound`
* :ref:`SHIMOTE_OUT2_DEF`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHIMOTE_OUT2_DEF_SE",
	    "args": [
	        "CID",
	        "CID2",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2922,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2923,
	            "command": "SHIMOTE_OUT2_DEF",
	            "args": [
	                "CID",
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2924,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2925,
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
