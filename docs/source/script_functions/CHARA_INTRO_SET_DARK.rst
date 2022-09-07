.. _CHARA_INTRO_SET_DARK:

CHARA_INTRO_SET_DARK
========================

.. code-block:: text

	CHARA_INTRO_SET_DARK(CID, NAME, ANOTHER, ANOTHER_RUBY, AFFLIATION, AFFLIATION_RUBY, EMBLEM_NAME)


Arguments
------------

* CID
* NAME
* ANOTHER
* ANOTHER_RUBY
* AFFLIATION
* AFFLIATION_RUBY
* EMBLEM_NAME

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_INTRO_SET_DARK",
	    "args": [
	        "CID",
	        "NAME",
	        "ANOTHER",
	        "ANOTHER_RUBY",
	        "AFFLIATION",
	        "AFFLIATION_RUBY",
	        "EMBLEM_NAME"
	    ],
	    "commandList": [
	        {
	            "row": 5339,
	            "command": "button_visible",
	            "args": [
	                "false",
	                "0.3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5340,
	            "command": "post_film",
	            "args": [
	                "0",
	                "0.5",
	                "filmMode_Mul",
	                "0.5",
	                "0",
	                "0",
	                "0",
	                "0",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5341,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5342,
	            "command": "if",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5343,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5344,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_02"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5345,
	            "command": "play_sound",
	            "args": [
	                "SE_266"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5346,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_03"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5347,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5348,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5349,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5350,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5351,
	            "command": "frame_visible",
	            "args": [
	                "false",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5352,
	            "command": "CHARA_INTRO",
	            "args": [
	                "CID",
	                "NAME",
	                "ANOTHER",
	                "ANOTHER_RUBY",
	                "AFFLIATION",
	                "AFFLIATION_RUBY",
	                "EMBLEM_NAME"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5353,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5354,
	            "command": "if",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5355,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_110"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5356,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_03"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5357,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_110"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5358,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5359,
	            "command": "wait",
	            "args": [
	                "1.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5360,
	            "command": "touch_wait",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5361,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5362,
	            "command": "chara_intro_end",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5363,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5364,
	            "command": "REMOVE_CHARA_INTRO",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5365,
	            "command": "fade_color",
	            "args": [
	                "0.5",
	                "0",
	                "0",
	                "0",
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5366,
	            "command": "frame_visible",
	            "args": [
	                "true",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5367,
	            "command": "Reset",
	            "args": [
	                "0.5",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5368,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5369,
	            "command": "button_visible",
	            "args": [
	                "false",
	                "0",
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

References
-------------
* :ref:`button_visible`
* :ref:`post_film`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`frame_visible`
* :ref:`CHARA_INTRO`
* :ref:`set_BG_effect`
* :ref:`touch_wait`
* :ref:`NO_EFFECT`
* :ref:`chara_intro_end`
* :ref:`REMOVE_CHARA_INTRO`
* :ref:`fade_color`
* :ref:`Reset`
