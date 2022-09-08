.. _SHOUT_MON:

SHOUT_MON
========================

.. code-block:: text

	SHOUT_MON()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SHOUT_MON():
		WFOUT_DEF()
		wait(0.2)
		play_sound(SE_014)
		set_camera_distortion(cameraType_Chara, true, EFF_007)
		SHOUT_0()
		effect_shake_bg(12, 0.4, 1.2, 1)
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
	    "name": "SHOUT_MON",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3378,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3379,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3380,
	            "command": "play_sound",
	            "args": [
	                "SE_014"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3381,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3382,
	            "command": "SHOUT_0",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3383,
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
	            "row": 3384,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3385,
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
