.. _TRANS_OUT_RIGHT_DEF:

TRANS_OUT_RIGHT_DEF
========================

.. code-block:: text

	TRANS_OUT_RIGHT_DEF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def TRANS_OUT_RIGHT_DEF():
		WFOUT_SHORT()
		screen_transout(1, 1.0)
		fade_color(0.25, 0, 0, 0, 1)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`screen_transout`
* :ref:`fade_color`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "TRANS_OUT_RIGHT_DEF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1674,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1675,
	            "command": "screen_transout",
	            "args": [
	                "1",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1676,
	            "command": "fade_color",
	            "args": [
	                "0.25",
	                "0",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
