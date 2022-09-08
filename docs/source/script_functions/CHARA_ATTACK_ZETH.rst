.. _CHARA_ATTACK_ZETH:

CHARA_ATTACK_ZETH
========================

.. code-block:: text

	CHARA_ATTACK_ZETH(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_ATTACK_ZETH(CID):
		WFOUT_SHORT()
		set_BG_effect(EFF_025)
		set_BG_effect_speed(EFF_025, 3)
		wait(0.3)
		play_sound(SE_061)
		set_camera_distortion(1, true, EFF_007)
		set_BG_effect(1, EFF_007)
		set_BG_effect_opacity(EFF_007, 0.6)
		set_BG_effect_speed(EFF_007, 1.0)
		set_BG_effect_trigger(2, 9)
		wait(0.3)
		set_BG_effect_trigger(2, 1)
		set_BG_effect(0, 0)
		set_camera_distortion(1, false, EFF_007)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_speed`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`set_camera_distortion`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_ATTACK_ZETH",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3606,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3607,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_025"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3608,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_025",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3609,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3610,
	            "command": "play_sound",
	            "args": [
	                "SE_061"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3611,
	            "command": "set_camera_distortion",
	            "args": [
	                "1",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3612,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3613,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3614,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3615,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3616,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3617,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3618,
	            "command": "set_BG_effect",
	            "args": [
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3619,
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
