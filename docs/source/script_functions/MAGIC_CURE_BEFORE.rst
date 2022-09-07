.. _MAGIC_CURE_BEFORE:

MAGIC_CURE_BEFORE
========================

.. code-block:: text

	MAGIC_CURE_BEFORE()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "MAGIC_CURE_BEFORE",
	    "args": [],
	    "commandList": [
	        {
	            "row": 4315,
	            "command": "play_sound",
	            "args": [
	                "SE_122"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4316,
	            "command": "fade_color",
	            "args": [
	                "1.0",
	                "255",
	                "255",
	                "255",
	                "1"
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
* :ref:`play_sound`
* :ref:`fade_color`
