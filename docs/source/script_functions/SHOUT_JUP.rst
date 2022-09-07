.. _SHOUT_JUP:

SHOUT_JUP
========================

.. code-block:: text

	SHOUT_JUP()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_JUP",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3342,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3343,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3344,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0215"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3345,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3346,
	            "command": "SHOUT_0",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3347,
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
	            "row": 3348,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3349,
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
* :ref:`SHOUT_0`
* :ref:`effect_shake_bg`
* :ref:`set_BG_effect_trigger`
