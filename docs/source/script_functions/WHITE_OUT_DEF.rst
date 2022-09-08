.. _WHITE_OUT_DEF:

WHITE_OUT_DEF
========================

.. code-block:: text

	WHITE_OUT_DEF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	WFOUT_SHORT()
	screen_fadeout(1.0, 255, 255, 255)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`screen_fadeout`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "WHITE_OUT_DEF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1660,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1661,
	            "command": "screen_fadeout",
	            "args": [
	                "1.0",
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
