.. _CHAPTER_INTRO_BAND:

CHAPTER_INTRO_BAND
========================

.. code-block:: text

	CHAPTER_INTRO_BAND(LABEL)


Arguments
------------

* LABEL

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHAPTER_INTRO_BAND(LABEL):
		chapter_intro(LABEL)
		chapter_intro_frame_visible(true, 0.7)

References
-------------
* :ref:`chapter_intro`
* :ref:`chapter_intro_frame_visible`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHAPTER_INTRO_BAND",
	    "args": [
	        "LABEL"
	    ],
	    "commandList": [
	        {
	            "row": 5381,
	            "command": "chapter_intro",
	            "args": [
	                "LABEL"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5382,
	            "command": "chapter_intro_frame_visible",
	            "args": [
	                "true",
	                "0.7"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
