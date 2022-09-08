.. _KAMITE_OUT2_FAST_SE:

KAMITE_OUT2_FAST_SE
========================

.. code-block:: text

	KAMITE_OUT2_FAST_SE(CID, CID2, SE)


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

	play_sound(SE)
	KAMITE_OUT2_FAST(CID, CID2)
	wait(0.5)
	BGMTUNE_DOWN_0(SE)

References
-------------
* :ref:`play_sound`
* :ref:`KAMITE_OUT2_FAST`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "KAMITE_OUT2_FAST_SE",
	    "args": [
	        "CID",
	        "CID2",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 2915,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2916,
	            "command": "KAMITE_OUT2_FAST",
	            "args": [
	                "CID",
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2917,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2918,
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
