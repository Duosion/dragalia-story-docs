.. _CHAPTER_INTRO_START:

CHAPTER_INTRO_START
========================

.. code-block:: text

	CHAPTER_INTRO_START()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHAPTER_INTRO_START():
		frame_visible(false)
		message_pos(1)
		window_enable(false)
		set_BG(0)

References
-------------
* :ref:`frame_visible`
* :ref:`message_pos`
* :ref:`window_enable`
* :ref:`set_BG`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHAPTER_INTRO_START",
	    "args": [],
	    "commandList": [
	        {
	            "row": 5374,
	            "command": "frame_visible",
	            "args": [
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5375,
	            "command": "message_pos",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5376,
	            "command": "window_enable",
	            "args": [
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5377,
	            "command": "set_BG",
	            "args": [
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
