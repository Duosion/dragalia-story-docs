.. _WHITE_OUT_MIDSHORT:

WHITE_OUT_MIDSHORT
========================

.. code-block:: text

	WHITE_OUT_MIDSHORT()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	WFOUT_SHORT()
	screen_fadeout(0.6, 255, 255, 255)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`screen_fadeout`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "WHITE_OUT_MIDSHORT",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1656,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1657,
	            "command": "screen_fadeout",
	            "args": [
	                "0.6",
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
