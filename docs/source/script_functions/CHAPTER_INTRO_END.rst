.. _CHAPTER_INTRO_END:

CHAPTER_INTRO_END
========================

.. code-block:: text

	CHAPTER_INTRO_END()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHAPTER_INTRO_END():
		message_pos(0)
		frame_visible(true)
		window_enable(true)
		chapter_intro(0)
		chapter_intro_frame_visible(false)

References
-------------
* :ref:`message_pos`
* :ref:`frame_visible`
* :ref:`window_enable`
* :ref:`chapter_intro`
* :ref:`chapter_intro_frame_visible`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHAPTER_INTRO_END",
	    "args": [],
	    "commandList": [
	        {
	            "row": 5390,
	            "command": "message_pos",
	            "args": [
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5391,
	            "command": "frame_visible",
	            "args": [
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5392,
	            "command": "window_enable",
	            "args": [
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5393,
	            "command": "chapter_intro",
	            "args": [
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5394,
	            "command": "chapter_intro_frame_visible",
	            "args": [
	                "false"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
