.. _SHIMOTE_OUT_SLOW_SE:

SHIMOTE_OUT_SLOW_SE
========================

.. code-block:: text

	SHIMOTE_OUT_SLOW_SE(CID, SE)


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

	play_sound(SE)
	SHIMOTE_OUT_SLOW(CID)
	wait(0.5)
	BGMTUNE_DOWN_0(SE)

References
-------------
* :ref:`play_sound`
* :ref:`SHIMOTE_OUT_SLOW`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHIMOTE_OUT_SLOW_SE",
	    "args": [
	        "CID",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2799,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2800,
	            "command": "SHIMOTE_OUT_SLOW",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2801,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2802,
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
