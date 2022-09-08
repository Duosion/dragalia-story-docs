.. _BGMFOUT_DEF:

BGMFOUT_DEF
========================

.. code-block:: text

	BGMFOUT_DEF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def BGMFOUT_DEF():
		stop_bgm(0.5)

References
-------------
* :ref:`stop_bgm`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "BGMFOUT_DEF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1115,
	            "command": "stop_bgm",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
