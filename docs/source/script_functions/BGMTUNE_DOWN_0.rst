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

.. code-block:: python

	def BGMTUNE_DOWN_0(BGM):
		set_volume(0, 0.5, BGM)

References
-------------
* :ref:`set_volume`

Table Implementation
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

Sample
-------------

.. code-block:: json

	{}
