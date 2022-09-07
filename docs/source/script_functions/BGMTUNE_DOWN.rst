.. _BGMTUNE_DOWN:

BGMTUNE_DOWN
========================

.. code-block:: text

	BGMTUNE_DOWN(BGM)


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
	    "name": "BGMTUNE_DOWN",
	    "args": [
	        "BGM"
	    ],
	    "commandList": [
	        {
	            "row": 1119,
	            "command": "set_volume",
	            "args": [
	                "0.5",
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
