.. _TUTORIAL_START:

TUTORIAL_START
========================

.. code-block:: text

	TUTORIAL_START(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	TUTORIAL_BUTTON_SETTING()
	window_type(NORMAL)
	fade_color(0.3, 0, 0, 0, 0.5, EaseOutCubic)
	chara_visible(CID, false)
	mnu_fade(CID, true, 0.15, 0.5, 1)
	mnu_fade(CID, false, 0.15, 1.0, 1)
	wait(0.15)
	frame_visible(true, 0.3)
	window_fadein(0, true)
	wait(0.3)
	chara_visible(CID, true)

References
-------------
* :ref:`TUTORIAL_BUTTON_SETTING`
* :ref:`window_type`
* :ref:`fade_color`
* :ref:`chara_visible`
* :ref:`mnu_fade`
* :ref:`wait`
* :ref:`frame_visible`
* :ref:`window_fadein`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "TUTORIAL_START",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5406,
	            "command": "TUTORIAL_BUTTON_SETTING",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5407,
	            "command": "window_type",
	            "args": [
	                "NORMAL"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5408,
	            "command": "fade_color",
	            "args": [
	                "0.3",
	                "0",
	                "0",
	                "0",
	                "0.5",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5409,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5410,
	            "command": "mnu_fade",
	            "args": [
	                "CID",
	                "true",
	                "0.15",
	                "0.5",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5411,
	            "command": "mnu_fade",
	            "args": [
	                "CID",
	                "false",
	                "0.15",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5412,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5413,
	            "command": "frame_visible",
	            "args": [
	                "true",
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5414,
	            "command": "window_fadein",
	            "args": [
	                "0",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5415,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5416,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
