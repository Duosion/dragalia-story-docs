.. _SHOUT_MON_EFF:

SHOUT_MON_EFF
========================

.. code-block:: text

	SHOUT_MON_EFF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_MON_EFF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3364,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3365,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3366,
	            "command": "play_sound",
	            "args": [
	                "SE_014"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3367,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3368,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3369,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3370,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3371,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3372,
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
	            "row": 3373,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3374,
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
