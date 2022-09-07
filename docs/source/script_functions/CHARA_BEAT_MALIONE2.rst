.. _CHARA_BEAT_MALIONE2:

CHARA_BEAT_MALIONE2
========================

.. code-block:: text

	CHARA_BEAT_MALIONE2(CID)


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
	    "name": "CHARA_BEAT_MALIONE2",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5623,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_145"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5624,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "100",
	                "60"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5625,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.3",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5626,
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
	            "row": 5627,
	            "command": "set_BG_effect_rotation",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "190"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5628,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5629,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0012"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5630,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0234"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5631,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5632,
	            "command": "wait",
	            "args": [
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5633,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "EFF_SCE_2D_CMN_145"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5634,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "-100",
	                "60"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5635,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.3",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5636,
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
	            "row": 5637,
	            "command": "set_BG_effect_rotation",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "340"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5638,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5639,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0012"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5640,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0234"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5641,
	            "command": "wait",
	            "args": [
	                "0.25"
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
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_scale`
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_rotation`
* :ref:`set_BG_effect_speed`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`
* :ref:`wait`
