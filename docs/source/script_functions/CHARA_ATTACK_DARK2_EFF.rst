.. _CHARA_ATTACK_DARK2_EFF:

CHARA_ATTACK_DARK2_EFF
========================

.. code-block:: text

	CHARA_ATTACK_DARK2_EFF(CID)


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
	    "name": "CHARA_ATTACK_DARK2_EFF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3575,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3576,
	            "command": "play_sound",
	            "args": [
	                "SE_043"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3577,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3578,
	            "command": "play_sound",
	            "args": [
	                "SE_044"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3579,
	            "command": "set_camera_distortion",
	            "args": [
	                "1",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3580,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3581,
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
	            "row": 3582,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_007",
	                "1.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3583,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_007",
	                "1.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3584,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3585,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3586,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3587,
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
* :ref:`set_BG_effect`
* :ref:`set_camera_distortion`
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_speed`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
