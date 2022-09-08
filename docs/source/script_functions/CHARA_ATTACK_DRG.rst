.. _CHARA_ATTACK_DRG:

CHARA_ATTACK_DRG
========================

.. code-block:: text

	CHARA_ATTACK_DRG(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_ATTACK_DRG(CID):
		WFOUT_SHORT()
		play_sound(SE_129)
		set_camera_distortion(1, true, EFF_007)
		set_BG_effect(EFF_007)
		set_BG_effect_opacity(EFF_007, 0.6)
		set_BG_effect_trigger(9)
		mnu_scale(CID, true, 0.15, 1.35, 1.35, EaseOutCubic)
		mnu_scale(CID, false, 0.15, 1, 1, EaseOutCubic)
		cmp_scale(CID, 0.3, 1, 1)
		wait(0.3)
		NO_EFFECT()
		set_camera_distortion(1, false, EFF_007)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`play_sound`
* :ref:`set_camera_distortion`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_trigger`
* :ref:`mnu_scale`
* :ref:`cmp_scale`
* :ref:`wait`
* :ref:`NO_EFFECT`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_ATTACK_DRG",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3639,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3640,
	            "command": "play_sound",
	            "args": [
	                "SE_129"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3641,
	            "command": "set_camera_distortion",
	            "args": [
	                "1",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3642,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3643,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3644,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3645,
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
	            "row": 3646,
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
	            "row": 3647,
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
	            "row": 3648,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3649,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3650,
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
