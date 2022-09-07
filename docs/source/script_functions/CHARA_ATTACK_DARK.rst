.. _CHARA_ATTACK_DARK:

CHARA_ATTACK_DARK
========================

.. code-block:: text

	CHARA_ATTACK_DARK(CID)


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
	    "name": "CHARA_ATTACK_DARK",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3533,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3534,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_070",
	                "EFF_071"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3535,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_070",
	                "79",
	                "0",
	                "225"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3536,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_071",
	                "79",
	                "0",
	                "225"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3537,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_070",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3538,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_071",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3539,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3540,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3541,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_070",
	                "0",
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3542,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_071",
	                "0",
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3543,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_046"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3544,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_046",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3545,
	            "command": "play_sound",
	            "args": [
	                "SE_060"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3546,
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
	            "row": 3547,
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
	            "row": 3548,
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
	            "row": 3549,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3550,
	            "command": "set_BG_effect",
	            "args": [
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
* :ref:`set_BG_effect_speed`
* :ref:`play_sound`
* :ref:`mnu_scale`
* :ref:`cmp_scale`
