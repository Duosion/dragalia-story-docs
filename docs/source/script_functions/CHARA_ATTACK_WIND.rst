.. _CHARA_ATTACK_WIND:

CHARA_ATTACK_WIND
========================

.. code-block:: text

	CHARA_ATTACK_WIND(CID)


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
	    "name": "CHARA_ATTACK_WIND",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3491,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3492,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_070",
	                "EFF_071"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3493,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_070",
	                "80",
	                "247",
	                "28"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3494,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_071",
	                "80",
	                "247",
	                "28"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3495,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_070",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3496,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_071",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3497,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3498,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3499,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3500,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_050"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3501,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_050",
	                "198",
	                "251",
	                "40"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3502,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_050",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3503,
	            "command": "play_sound",
	            "args": [
	                "SE_064"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3504,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "true",
	                "0.15",
	                "1.35",
	                "1.35",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3505,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "false",
	                "0.15",
	                "1",
	                "1",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3506,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.3",
	                "1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3507,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3508,
	            "command": "set_BG_effect",
	            "args": [
	                "0",
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

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
* :ref:`NO_EFFECT`
* :ref:`set_BG_effect_speed`
* :ref:`play_sound`
* :ref:`mnu_scale`
* :ref:`cmp_scale`
