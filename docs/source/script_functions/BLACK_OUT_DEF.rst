.. _BLACK_OUT_DEF:

BLACK_OUT_DEF
========================

.. code-block:: text

	BLACK_OUT_DEF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "BLACK_OUT_DEF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1627,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1628,
	            "command": "screen_fadeout",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`screen_fadeout`
