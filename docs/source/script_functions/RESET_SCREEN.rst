.. _RESET_SCREEN:

RESET_SCREEN
========================

.. code-block:: text

	RESET_SCREEN()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	Reset(0, 0)
	ResetLerp(0, 0)
	Reset(0, 1)
	ResetLerp(0, 1)
	Reset(0, 2)
	ResetLerp(0, 2)

References
-------------
* :ref:`Reset`
* :ref:`ResetLerp`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "RESET_SCREEN",
	    "args": [],
	    "commandList": [
	        {
	            "row": 5142,
	            "command": "Reset",
	            "args": [
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5143,
	            "command": "ResetLerp",
	            "args": [
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5144,
	            "command": "Reset",
	            "args": [
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5145,
	            "command": "ResetLerp",
	            "args": [
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5146,
	            "command": "Reset",
	            "args": [
	                "0",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5147,
	            "command": "ResetLerp",
	            "args": [
	                "0",
	                "2"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
