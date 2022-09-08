.. _CHARA_ATTACK_LIGHT:

CHARA_ATTACK_LIGHT
========================

.. code-block:: text

	CHARA_ATTACK_LIGHT(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_ATTACK_LIGHT(CID):
		WFOUT_SHORT()
		set_BG_effect(EFF_070, EFF_071)
		set_BG_effect_opacity(EFF_070, 0.8)
		set_BG_effect_opacity(EFF_071, 0.8)
		set_BG_effect_trigger(9, 9)
		wait(0.8)
		NO_EFFECT()
		set_BG_effect(EFF_108)
		set_BG_effect_pos(EFF_108, 0, -100)
		set_BG_effect_speed(EFF_108, 2)
		play_sound(SE_061)
		mnu_scale(CID, true, 0.15, 1.35, 1.35, EaseOutCubic)
		mnu_scale(CID, false, 0.15, 1, 1, EaseOutCubic)
		cmp_scale(CID, 0.3, 1, 1)
		wait(0.1)
		set_BG_effect_opacity(EFF_108, 0, 0.5)
		wait(0.5)
		set_BG_effect(0, 0)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
* :ref:`NO_EFFECT`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_speed`
* :ref:`play_sound`
* :ref:`mnu_scale`
* :ref:`cmp_scale`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_ATTACK_LIGHT",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3512,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3513,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_070",
	                "EFF_071"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3514,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_070",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3515,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_071",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3516,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3517,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3518,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3519,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_108"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3520,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_108",
	                "0",
	                "-100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3521,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_108",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3522,
	            "command": "play_sound",
	            "args": [
	                "SE_061"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3523,
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
	            "row": 3524,
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
	            "row": 3525,
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
	            "row": 3526,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3527,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_108",
	                "0",
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3528,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3529,
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
