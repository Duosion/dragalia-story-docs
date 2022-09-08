.. _CHARA_BEAT3_WIND_BEFORE_IN:

CHARA_BEAT3_WIND_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT3_WIND_BEFORE_IN(CID, int, CID2, int2, CID3, int3)


Arguments
------------

* CID
* int
* CID2
* int2
* CID3
* int3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	set_BG_effect(EFF_061)
	set_BG_effect_speed(EFF_061, 2.0)
	wait(0.05)
	play_sound(SE_064)
	wait(0.15)
	chara_face(CID, int)
	chara_face(CID2, int2)
	chara_face(CID3, int3)
	chara_shake_h(CID, 2, true)
	chara_shake_h(CID2, 2, true)
	chara_shake_h(CID3, 2, true)
	wait(0.7)
	chara_shake_h(CID, 2, false)
	chara_shake_h(CID2, 2, false)
	chara_shake_h(CID3, 2, false)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_speed`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`chara_face`
* :ref:`chara_shake_h`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT3_WIND_BEFORE_IN",
	    "args": [
	        "CID",
	        "int",
	        "CID2",
	        "int2",
	        "CID3",
	        "int3"
	    ],
	    "commandList": [
	        {
	            "row": 3993,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_061"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3994,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_061",
	                "2.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3995,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3996,
	            "command": "play_sound",
	            "args": [
	                "SE_064"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3997,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3998,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3999,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4000,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4001,
	            "command": "chara_shake_h",
	            "args": [
	                "CID",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4002,
	            "command": "chara_shake_h",
	            "args": [
	                "CID2",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4003,
	            "command": "chara_shake_h",
	            "args": [
	                "CID3",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4004,
	            "command": "wait",
	            "args": [
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4005,
	            "command": "chara_shake_h",
	            "args": [
	                "CID",
	                "2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4006,
	            "command": "chara_shake_h",
	            "args": [
	                "CID2",
	                "2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4007,
	            "command": "chara_shake_h",
	            "args": [
	                "CID3",
	                "2",
	                "false"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
