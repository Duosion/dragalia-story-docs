.. _TRANS_IN_RIGHT_DEF:

TRANS_IN_RIGHT_DEF
========================

.. code-block:: text

	TRANS_IN_RIGHT_DEF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	fade_color(0.25, 0, 0, 0, 0)
	screen_transin(1, 1.0)

References
-------------
* :ref:`fade_color`
* :ref:`screen_transin`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "TRANS_IN_RIGHT_DEF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1670,
	            "command": "fade_color",
	            "args": [
	                "0.25",
	                "0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1671,
	            "command": "screen_transin",
	            "args": [
	                "1",
	                "1.0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
