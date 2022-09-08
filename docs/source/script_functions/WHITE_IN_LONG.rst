.. _WHITE_IN_LONG:

WHITE_IN_LONG
========================

.. code-block:: text

	WHITE_IN_LONG()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def WHITE_IN_LONG():
		screen_fadein(2.0, 255, 255, 255)

References
-------------
* :ref:`screen_fadein`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "WHITE_IN_LONG",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1650,
	            "command": "screen_fadein",
	            "args": [
	                "2.0",
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
