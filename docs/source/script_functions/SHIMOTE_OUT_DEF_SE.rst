.. _SHIMOTE_OUT_DEF_SE:

SHIMOTE_OUT_DEF_SE
========================

.. code-block:: text

	SHIMOTE_OUT_DEF_SE(CID, SE)


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

	def SHIMOTE_OUT_DEF_SE(CID, SE):
		play_sound(SE)
		SHIMOTE_OUT_DEF(CID)
		wait(0.5)
		BGMTUNE_DOWN_0(SE)

References
-------------
* :ref:`play_sound`
* :ref:`SHIMOTE_OUT_DEF`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHIMOTE_OUT_DEF_SE",
	    "args": [
	        "CID",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2792,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2793,
	            "command": "SHIMOTE_OUT_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2794,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2795,
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
