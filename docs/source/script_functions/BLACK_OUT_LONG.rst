.. _BLACK_OUT_LONG:

BLACK_OUT_LONG
========================

.. code-block:: text

	BLACK_OUT_LONG()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	WFOUT_SHORT()
	screen_fadeout(2.0, 0, 0, 0)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`screen_fadeout`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "BLACK_OUT_LONG",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1639,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1640,
	            "command": "screen_fadeout",
	            "args": [
	                "2.0",
	                "0",
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
