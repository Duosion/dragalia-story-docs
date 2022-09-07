.. _BGMTUNE_DOWN_0:

BGMTUNE_DOWN_0
========================

.. code-block:: text

	BGMTUNE_DOWN_0(BGM)


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
	    "name": "BGMTUNE_DOWN_0",
	    "args": [
	        "BGM"
	    ],
	    "commandList": [
	        {
	            "row": 1123,
	            "command": "set_volume",
	            "args": [
	                "0",
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
