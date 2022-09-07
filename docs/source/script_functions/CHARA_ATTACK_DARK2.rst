.. _CHARA_ATTACK_DARK2:

CHARA_ATTACK_DARK2
========================

.. code-block:: text

	CHARA_ATTACK_DARK2(CID)


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
	    "name": "CHARA_ATTACK_DARK2",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3591,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3592,
	            "command": "play_sound",
	            "args": [
	                "SE_043"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3593,
	            "command": "play_sound",
	            "args": [
	                "SE_044"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3594,
	            "command": "set_camera_distortion",
	            "args": [
	                "1",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3595,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3596,
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
	            "row": 3597,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "1.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3598,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3599,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3600,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3601,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3602,
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
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_speed`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
