.. _BLACK_OUT_DEF_STOP:

BLACK_OUT_DEF_STOP
========================

.. code-block:: text

	BLACK_OUT_DEF_STOP()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def BLACK_OUT_DEF_STOP():
		RESET_TEXT()
		window_fadeout(0, true)
		BGMFOUT_DEF()
		SEFOUT_DEF()
		screen_fadeout(1.0, 0, 0, 0)

References
-------------
* :ref:`RESET_TEXT`
* :ref:`window_fadeout`
* :ref:`BGMFOUT_DEF`
* :ref:`SEFOUT_DEF`
* :ref:`screen_fadeout`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "BLACK_OUT_DEF_STOP",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1579,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1580,
	            "command": "window_fadeout",
	            "args": [
	                "0",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1581,
	            "command": "BGMFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1582,
	            "command": "SEFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1583,
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

Sample
-------------

.. code-block:: json

	{}
