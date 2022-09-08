.. _SHOUT_MID:

SHOUT_MID
========================

.. code-block:: text

	SHOUT_MID()


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
	play_sound(SE_STORY_COMMON_0212)
	set_camera_distortion(cameraType_Chara, true, EFF_007)
	SHOUT_0()
	effect_shake_bg(12, 0.5, 1.5, 1)
	set_BG_effect_trigger(1)
	set_camera_distortion(cameraType_Chara, false, EFF_007)

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`set_camera_distortion`
* :ref:`SHOUT_0`
* :ref:`effect_shake_bg`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_MID",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3278,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3279,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3280,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0212"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3281,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3282,
	            "command": "SHOUT_0",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3283,
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
	            "row": 3284,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3285,
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
