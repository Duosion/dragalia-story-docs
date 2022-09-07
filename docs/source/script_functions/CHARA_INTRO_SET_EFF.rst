.. _CHARA_INTRO_SET_EFF:

CHARA_INTRO_SET_EFF
========================

.. code-block:: text

	CHARA_INTRO_SET_EFF(CID, NAME, ANOTHER, ANOTHER_RUBY, AFFLIATION, AFFLIATION_RUBY, EMBLEM_NAME, EFF, EFF2, trigger, trigger2)


Arguments
------------

* CID
* NAME
* ANOTHER
* ANOTHER_RUBY
* AFFLIATION
* AFFLIATION_RUBY
* EMBLEM_NAME
* EFF
* EFF2
* trigger
* trigger2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_INTRO_SET_EFF",
	    "args": [
	        "CID",
	        "NAME",
	        "ANOTHER",
	        "ANOTHER_RUBY",
	        "AFFLIATION",
	        "AFFLIATION_RUBY",
	        "EMBLEM_NAME",
	        "EFF",
	        "EFF2",
	        "trigger",
	        "trigger2"
	    ],
	    "commandList": [
	        {
	            "row": 5301,
	            "command": "screen_fadeout",
	            "args": [
	                "0.5",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5302,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5303,
	            "command": "button_visible",
	            "args": [
	                "false",
	                "0.3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5304,
	            "command": "post_film",
	            "args": [
	                "0",
	                "0",
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
	            "row": 5305,
	            "command": "screen_fadein",
	            "args": [
	                "0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5306,
	            "command": "if",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5307,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5308,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_02"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5309,
	            "command": "play_sound",
	            "args": [
	                "SE_266"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5310,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_03"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5311,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5312,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5313,
	            "command": "play_sound",
	            "args": [
	                "SE_207"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5314,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5315,
	            "command": "frame_visible",
	            "args": [
	                "false",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5316,
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
	            "row": 5317,
	            "command": "wait",
	            "args": [
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5318,
	            "command": "if",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_01"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5319,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_110"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5320,
	            "command": "elif",
	            "args": [
	                "EMBLEM_NAME",
	                "Icon_Emblem_Story_03"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5321,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_110"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5322,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5323,
	            "command": "wait",
	            "args": [
	                "1.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5324,
	            "command": "touch_wait",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5325,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5326,
	            "command": "chara_intro_end",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5327,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5328,
	            "command": "REMOVE_CHARA_INTRO",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5329,
	            "command": "frame_visible",
	            "args": [
	                "true",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5330,
	            "command": "screen_fadeout",
	            "args": [
	                "0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5331,
	            "command": "Reset",
	            "args": [
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5332,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF",
	                "EFF2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5333,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "trigger",
	                "trigger2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5334,
	            "command": "screen_fadein",
	            "args": [
	                "0.5",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5335,
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
* :ref:`screen_fadeout`
* :ref:`NO_EFFECT`
* :ref:`button_visible`
* :ref:`post_film`
* :ref:`screen_fadein`
* :ref:`play_sound`
* :ref:`frame_visible`
* :ref:`CHARA_INTRO`
* :ref:`wait`
* :ref:`set_BG_effect`
* :ref:`touch_wait`
* :ref:`chara_intro_end`
* :ref:`REMOVE_CHARA_INTRO`
* :ref:`Reset`
* :ref:`set_BG_effect_trigger`
