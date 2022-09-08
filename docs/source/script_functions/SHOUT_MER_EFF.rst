.. _SHOUT_MER_EFF:

SHOUT_MER_EFF
========================

.. code-block:: text

	SHOUT_MER_EFF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	WFOUT_DEF()
	wait(0.2)
	play_sound(SE_STORY_COMMON_0214)
	set_camera_distortion(cameraType_Chara, true, EFF_007)
	set_BG_effect(1, 1, EFF_007)
	set_BG_effect_opacity(EFF_007, 0.5)
	set_BG_effect_speed(EFF_007, 1.3)
	set_BG_effect_trigger(2, 2, 9)
	effect_shake_bg(12, 0.4, 1.2, 1)
	set_BG_effect_trigger(2, 2, 1)
	set_camera_distortion(cameraType_Chara, false, EFF_007)

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

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_MER_EFF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3289,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3290,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3291,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0214"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3292,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3293,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3294,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3295,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3296,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3297,
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
	            "row": 3298,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3299,
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
