.. _CHARA_ATTACK_DRG_EFF:

CHARA_ATTACK_DRG_EFF
========================

.. code-block:: text

	CHARA_ATTACK_DRG_EFF(CID)


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
	    "name": "CHARA_ATTACK_DRG_EFF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3654,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3655,
	            "command": "play_sound",
	            "args": [
	                "SE_129"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3656,
	            "command": "set_camera_distortion",
	            "args": [
	                "1",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3657,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3658,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3659,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3660,
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
	            "row": 3661,
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
	            "row": 3662,
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
	            "row": 3663,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3664,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3665,
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
