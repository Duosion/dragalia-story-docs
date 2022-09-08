.. _SCREEN_FLASH_WHITE_DEF:

SCREEN_FLASH_WHITE_DEF
========================

.. code-block:: text

	SCREEN_FLASH_WHITE_DEF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SCREEN_FLASH_WHITE_DEF():
		screen_flash(0.04, 255, 255, 255)

References
-------------
* :ref:`screen_flash`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SCREEN_FLASH_WHITE_DEF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3028,
	            "command": "screen_flash",
	            "args": [
	                "0.04",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
