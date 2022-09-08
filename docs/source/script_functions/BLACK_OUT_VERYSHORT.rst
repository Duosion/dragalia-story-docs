.. _BLACK_OUT_VERYSHORT:

BLACK_OUT_VERYSHORT
========================

.. code-block:: text

	BLACK_OUT_VERYSHORT()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def BLACK_OUT_VERYSHORT():
		WFOUT_SHORT()
		screen_fadeout(0.3, 0, 0, 0)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`screen_fadeout`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "BLACK_OUT_VERYSHORT",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1631,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1632,
	            "command": "screen_fadeout",
	            "args": [
	                "0.3",
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
