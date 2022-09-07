.. _SHOUT_BRY:

SHOUT_BRY
========================

.. code-block:: text

	SHOUT_BRY()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_BRY",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3317,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3318,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3319,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0213"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3320,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3321,
	            "command": "SHOUT_0",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3322,
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
	            "row": 3323,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3324,
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

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`set_camera_distortion`
* :ref:`SHOUT_0`
* :ref:`effect_shake_bg`
* :ref:`set_BG_effect_trigger`
