.. _KAMITE_OUT_SLOW_SE:

KAMITE_OUT_SLOW_SE
========================

.. code-block:: text

	KAMITE_OUT_SLOW_SE(CID, SE)


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
	KAMITE_OUT_SLOW(CID)
	wait(0.5)
	BGMTUNE_DOWN_0(SE)

References
-------------
* :ref:`play_sound`
* :ref:`KAMITE_OUT_SLOW`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "KAMITE_OUT_SLOW_SE",
	    "args": [
	        "CID",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2778,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2779,
	            "command": "KAMITE_OUT_SLOW",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2780,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2781,
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
