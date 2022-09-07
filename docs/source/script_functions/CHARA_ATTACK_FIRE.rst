.. _CHARA_ATTACK_FIRE:

CHARA_ATTACK_FIRE
========================

.. code-block:: text

	CHARA_ATTACK_FIRE(CID)


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
	    "name": "CHARA_ATTACK_FIRE",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3449,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3450,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_070",
	                "EFF_071"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3451,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_070",
	                "255",
	                "138",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3452,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_071",
	                "255",
	                "138",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3453,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_070",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3454,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_071",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3455,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3456,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3457,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3458,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_050"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3459,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_050",
	                "255",
	                "15",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3460,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_050",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3461,
	            "command": "play_sound",
	            "args": [
	                "SE_062"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3462,
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
	            "row": 3463,
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
	            "row": 3464,
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
	            "row": 3465,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3466,
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
