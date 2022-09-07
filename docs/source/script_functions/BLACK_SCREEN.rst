.. _BLACK_SCREEN:

BLACK_SCREEN
========================

.. code-block:: text

	BLACK_SCREEN()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "BLACK_SCREEN",
	    "args": [],
	    "commandList": [
	        {
	            "row": 5156,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5157,
	            "command": "fade_color",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0",
	                "0.7"
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
* :ref:`WFOUT_SHORT`
* :ref:`fade_color`
