.. _BGMTUNE_DEF:

BGMTUNE_DEF
========================

.. code-block:: text

	BGMTUNE_DEF(BGM)


Arguments
------------

* BGM

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "BGMTUNE_DEF",
	    "args": [
	        "BGM"
	    ],
	    "commandList": [
	        {
	            "row": 1127,
	            "command": "set_volume",
	            "args": [
	                "1.0",
	                "0.5",
	                "BGM"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`set_volume`
