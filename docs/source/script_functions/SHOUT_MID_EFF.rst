.. _SHOUT_MID_EFF:

SHOUT_MID_EFF
========================

.. code-block:: text

	SHOUT_MID_EFF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_MID_EFF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3264,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3265,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3266,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0212"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3267,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3268,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3269,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3270,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3271,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3272,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.5",
	                "1.5",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3273,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3274,
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
