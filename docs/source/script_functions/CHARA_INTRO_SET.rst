.. _CHARA_INTRO_SET:

CHARA_INTRO_SET
========================

.. code-block:: text

	CHARA_INTRO_SET(CID, NAME, ANOTHER, ANOTHER_RUBY, AFFLIATION, AFFLIATION_RUBY, EMBLEM_NAME)


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
	    "name": "CHARA_INTRO_SET",
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
	            "row": 5268,
	            "command": "button_visible",
	            "args": [
	                "false",
	                "0.3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5269,
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
	            "row": 5270,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5271,
	            "command": "if",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5272,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5273,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_02"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5274,
	            "command": "play_sound",
	            "args": [
	                "SE_266"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5275,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_03"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5276,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5277,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5278,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5279,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5280,
	            "command": "frame_visible",
	            "args": [
	                "false",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5281,
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
	            "row": 5282,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5283,
	            "command": "if",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5284,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_110"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5285,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_03"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5286,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_110"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5287,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5288,
	            "command": "wait",
	            "args": [
	                "1.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5289,
	            "command": "touch_wait",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5290,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5291,
	            "command": "chara_intro_end",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5292,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5293,
	            "command": "REMOVE_CHARA_INTRO",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5294,
	            "command": "frame_visible",
	            "args": [
	                "true",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5295,
	            "command": "Reset",
	            "args": [
	                "0.5",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5296,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5297,
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
* :ref:`Reset`
