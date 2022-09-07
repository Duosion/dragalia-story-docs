.. _MAGIC_CURE_AFTER:

MAGIC_CURE_AFTER
========================

.. code-block:: text

	MAGIC_CURE_AFTER()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "MAGIC_CURE_AFTER",
	    "args": [],
	    "commandList": [
	        {
	            "row": 4320,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_050"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4321,
	            "command": "fade_color",
	            "args": [
	                "1.0",
	                "255",
	                "255",
	                "255",
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

References
-------------
* :ref:`set_BG_effect`
* :ref:`fade_color`
