.. _SCREEN_FLASH_RED_DEF:

SCREEN_FLASH_RED_DEF
========================

.. code-block:: text

	SCREEN_FLASH_RED_DEF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SCREEN_FLASH_RED_DEF():
		screen_flash(0.04, 255, 0, 0)

References
-------------
* :ref:`screen_flash`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SCREEN_FLASH_RED_DEF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3031,
	            "command": "screen_flash",
	            "args": [
	                "0.04",
	                "255",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
