.. _CHANGE_DRAGON:

CHANGE_DRAGON
========================

.. code-block:: text

	CHANGE_DRAGON(CID, CID2, SE)


Arguments
------------

* CID
* CID2
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHANGE_DRAGON(CID, CID2, SE):
		NO_EMO(CID)
		WFOUT_SHORT()
		set_BG_effect(EFF_070, EFF_071, EFF_020)
		set_BG_effect_trigger(8, 8, 2)
		play_sound(SE_210)
		wait(0.9)
		fade_color(0.2, 255, 255, 255, 1)
		NO_EFFECT()
		set_BG_effect(EFF_020)
		CHARA_RESET(CID)
		CHARA_SET(M, M, C, CID2, 1)
		set_BG_effect(EFF_020)
		set_BG_effect_trigger(1)
		fade_color(1.5, 255, 255, 255, 0.7)
		set_BG_effect_trigger(1)
		fade_color(1.0, 255, 255, 255, 0.4)
		set_camera_distortion(1, true, EFF_007)
		set_BG_effect(EFF_007)
		set_BG_effect_speed(EFF_007, 0.2)
		set_BG_effect_trigger(8)
		fade_color(0.5, 255, 255, 255, 0.2)
		set_BG_effect_trigger(1)
		fade_color(2.0, 255, 255, 255, 0.0)
		NO_EFFECT()
		play_sound(SE)
		set_BG_effect(EFF_007)
		set_BG_effect_speed(EFF_007, 1.5)
		set_BG_effect_trigger(8)
		effect_shake_bg(12, 0.5, 1.5, 1)
		NO_EFFECT()
		set_camera_distortion(1, false, EFF_007)

References
-------------
* :ref:`NO_EMO`
* :ref:`WFOUT_SHORT`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`play_sound`
* :ref:`wait`
* :ref:`fade_color`
* :ref:`NO_EFFECT`
* :ref:`CHARA_RESET`
* :ref:`CHARA_SET`
* :ref:`set_camera_distortion`
* :ref:`set_BG_effect_speed`
* :ref:`effect_shake_bg`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHANGE_DRAGON",
	    "args": [
	        "CID",
	        "CID2",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 3064,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3065,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3066,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_070",
	                "EFF_071",
	                "EFF_020"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3067,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8",
	                "8",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3068,
	            "command": "play_sound",
	            "args": [
	                "SE_210"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3069,
	            "command": "wait",
	            "args": [
	                "0.9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3070,
	            "command": "fade_color",
	            "args": [
	                "0.2",
	                "255",
	                "255",
	                "255",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3071,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3072,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_020"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3073,
	            "command": "CHARA_RESET",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3074,
	            "command": "CHARA_SET",
	            "args": [
	                "M",
	                "M",
	                "C",
	                "CID2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3075,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_020"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3076,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3077,
	            "command": "fade_color",
	            "args": [
	                "1.5",
	                "255",
	                "255",
	                "255",
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3078,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3079,
	            "command": "fade_color",
	            "args": [
	                "1.0",
	                "255",
	                "255",
	                "255",
	                "0.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3080,
	            "command": "set_camera_distortion",
	            "args": [
	                "1",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3081,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3082,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3083,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3084,
	            "command": "fade_color",
	            "args": [
	                "0.5",
	                "255",
	                "255",
	                "255",
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3085,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3086,
	            "command": "fade_color",
	            "args": [
	                "2.0",
	                "255",
	                "255",
	                "255",
	                "0.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3087,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3088,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3089,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3090,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3091,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3092,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.5",
	                "1.5",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3093,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3094,
	            "command": "set_camera_distortion",
	            "args": [
	                "1",
	                "false",
	                "EFF_007"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
