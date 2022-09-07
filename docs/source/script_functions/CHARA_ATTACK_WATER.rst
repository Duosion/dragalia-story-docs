.. _CHARA_ATTACK_WATER:

CHARA_ATTACK_WATER
========================

.. code-block:: text

	CHARA_ATTACK_WATER(CID)


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
	    "name": "CHARA_ATTACK_WATER",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3470,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3471,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_070",
	                "EFF_071"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3472,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_070",
	                "4",
	                "144",
	                "253"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3473,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_071",
	                "4",
	                "144",
	                "253"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3474,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_070",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3475,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_071",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3476,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3477,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3478,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3479,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_050"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3480,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_050",
	                "4",
	                "144",
	                "253"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3481,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_050",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3482,
	            "command": "play_sound",
	            "args": [
	                "SE_063"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3483,
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
	            "row": 3484,
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
	            "row": 3485,
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
	            "row": 3486,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3487,
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
