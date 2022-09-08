.. _BLACK_OUT_MIDSHORT:

BLACK_OUT_MIDSHORT
========================

.. code-block:: text

	BLACK_OUT_MIDSHORT()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def BLACK_OUT_MIDSHORT():
		WFOUT_SHORT()
		screen_fadeout(0.6, 0, 0, 0)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`screen_fadeout`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "BLACK_OUT_MIDSHORT",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1635,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1636,
	            "command": "screen_fadeout",
	            "args": [
	                "0.6",
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
