.. _WHITE_OUT_LONG:

WHITE_OUT_LONG
========================

.. code-block:: text

	WHITE_OUT_LONG()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "WHITE_OUT_LONG",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1664,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1665,
	            "command": "screen_fadeout",
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

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`screen_fadeout`
