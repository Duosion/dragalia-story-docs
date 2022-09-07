.. _CHARA_ATTACK_MC_009:

CHARA_ATTACK_MC_009
========================

.. code-block:: text

	CHARA_ATTACK_MC_009(CID)


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
	    "name": "CHARA_ATTACK_MC_009",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3555,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3556,
	            "command": "play_sound",
	            "args": [
	                "SE_043"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3557,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_010",
	                "EFF_011",
	                "EFF_046"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3558,
	            "command": "play_sound",
	            "args": [
	                "SE_044"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3559,
	            "command": "set_camera_distortion",
	            "args": [
	                "1",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3560,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_046",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3561,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_046",
	                "46",
	                "9",
	                "56"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3562,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_007",
	                "178",
	                "120",
	                "221"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3563,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_046",
	                "2.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3564,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "1.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3565,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_046",
	                "2.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3566,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3567,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9",
	                "9",
	                "1",
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3568,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3569,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3570,
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

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_camera_distortion`
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_speed`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
