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

.. code-block:: python

	def BGMTUNE_DEF(BGM):
		set_volume(1.0, 0.5, BGM)

References
-------------
* :ref:`set_volume`

Table Implementation
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

Sample
-------------

.. code-block:: json

	{}
