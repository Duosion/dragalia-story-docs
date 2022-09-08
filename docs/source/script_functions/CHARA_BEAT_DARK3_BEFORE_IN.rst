.. _CHARA_BEAT_DARK3_BEFORE_IN:

CHARA_BEAT_DARK3_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_DARK3_BEFORE_IN(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	set_BG_effect(1, 1, EFF_020)
	set_BG_effect_color(EFF_020, 213, 0, 255, 1)
	set_BG_effect_speed(EFF_020, 0.8)
	wait(1.0)
	play_sound(SE_044)
	wait(0.1)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_speed`
* :ref:`wait`
* :ref:`play_sound`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_DARK3_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4037,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_020"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4038,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_020",
	                "213",
	                "0",
	                "255",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4039,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_020",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4040,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4041,
	            "command": "play_sound",
	            "args": [
	                "SE_044"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4042,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
