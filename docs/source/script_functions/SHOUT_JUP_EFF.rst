.. _SHOUT_JUP_EFF:

SHOUT_JUP_EFF
========================

.. code-block:: text

	SHOUT_JUP_EFF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_JUP_EFF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3328,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3329,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3330,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0215"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3331,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3332,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3333,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3334,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3335,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8",
	                "8",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3336,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.4",
	                "1.2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3337,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3338,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
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
* :ref:`WFOUT_DEF`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`set_camera_distortion`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_speed`
* :ref:`set_BG_effect_trigger`
* :ref:`effect_shake_bg`
