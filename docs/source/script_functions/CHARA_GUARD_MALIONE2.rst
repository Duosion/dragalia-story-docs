.. _CHARA_GUARD_MALIONE2:

CHARA_GUARD_MALIONE2
========================

.. code-block:: text

	CHARA_GUARD_MALIONE2(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_GUARD_MALIONE2",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5644,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5645,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "0",
	                "EFF_SCE_2D_CMN_089"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5646,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "-150",
	                "145"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5647,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.3",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5648,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "255",
	                "198",
	                "107"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5649,
	            "command": "set_BG_effect_rotation",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "-35"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5650,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5651,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0013"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5652,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5653,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5654,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "EFF_SCE_2D_CMN_145",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5655,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "150",
	                "180"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5656,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.3",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5657,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "255",
	                "198",
	                "107"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5658,
	            "command": "set_BG_effect_rotation",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "210"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5659,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5660,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0013"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5661,
	            "command": "wait",
	            "args": [
	                "0.25"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`SCREEN_FLASH_WHITE_DEF`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_scale`
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_rotation`
* :ref:`set_BG_effect_speed`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`
* :ref:`wait`
