.. _CHARA_BEAT3_BEFORE_IN:

CHARA_BEAT3_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT3_BEFORE_IN(WEAPON, eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3)


Arguments
------------

* WEAPON
* eye
* lip
* CID
* int
* eye2
* lip2
* CID2
* int2
* eye3
* lip3
* CID3
* int3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_BEAT3_BEFORE_IN(WEAPON, eye, lip, CID, int, eye2, lip2, CID2, int2, eye3, lip3, CID3, int3):
		if WEAPON == "BOW":
			set_BG_effect(EFF_092)
			set_BG_effect_trigger(8)
			set_BG_effect_speed(EFF_092, 1.5)
			wait(0.15)
			play_sound(SE_239)
			set_BG_effect(1, EFF_001)
			set_BG_effect_pos(EFF_001, -160, 50, 0, 1)
			set_BG_effect_speed(EFF_001, 1.5)
			wait(0.15)
			play_sound(SE_239)
			NO_EFFECT()
			set_BG_effect(EFF_001)
			set_BG_effect_pos(EFF_001, 160, 50, 0, 1)
			set_BG_effect_speed(EFF_001, 1.5)
			wait(0.15)
		elif WEAPON == "AXE":
			set_BG_effect(EFF_090, EFF_001)
			set_BG_effect_speed(EFF_090, 0.75)
			set_BG_effect_scale(EFF_090, 2.0, 1.5)
			set_BG_effect_pos(EFF_090, 150, 0)
			set_BG_effect_pos(EFF_001, 150, 50)
			play_sound(SE_116)
			stop_se(0.1)
			wait(0.15)
			play_sound(SE_116)
			set_BG_effect(1, 0, EFF_001)
			set_BG_effect_pos(EFF_001, 0, 0)
			stop_se(0.1)
			wait(0.15)
			play_sound(SE_116)
			set_BG_effect(1, 0, 0, EFF_001)
			set_BG_effect_pos(EFF_001, -150, -50)
			wait(0.15)
		elif WEAPON == "WIND":
			set_BG_effect(EFF_061)
			set_BG_effect_speed(EFF_061, 2.0)
			wait(0.05)
			play_sound(SE_064)
			wait(0.15)
		if WEAPON == "WIND":
			c_face(eye, lip, CID, int)
			c_face(eye2, lip2, CID2, int2)
			c_face(eye3, lip3, CID3, int3)
			chara_shake_h(CID, 2, true)
			chara_shake_h(CID2, 2, true)
			chara_shake_h(CID3, 2, true)
			wait(0.7)
			chara_shake_h(CID, 2, false)
			chara_shake_h(CID2, 2, false)
			chara_shake_h(CID3, 2, false)
		else:
			c_face(eye, lip, CID, int)
			c_face(eye2, lip2, CID2, int2)
			c_face(eye3, lip3, CID3, int3)
			c_swing2_h_fast(CID)
			c_swing2_h_fast(CID2)
			c_swing2_h_fast(CID3)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`set_BG_effect_speed`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`set_BG_effect_pos`
* :ref:`NO_EFFECT`
* :ref:`set_BG_effect_scale`
* :ref:`stop_se`
* :ref:`c_face`
* :ref:`chara_shake_h`
* :ref:`c_swing2_h_fast`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT3_BEFORE_IN",
	    "args": [
	        "WEAPON",
	        "eye",
	        "lip",
	        "CID",
	        "int",
	        "eye2",
	        "lip2",
	        "CID2",
	        "int2",
	        "eye3",
	        "lip3",
	        "CID3",
	        "int3"
	    ],
	    "commandList": [
	        {
	            "row": 4075,
	            "command": "if",
	            "args": [
	                "WEAPON",
	                "BOW"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4076,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_092"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4077,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4078,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_092",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4079,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4080,
	            "command": "play_sound",
	            "args": [
	                "SE_239"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4081,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4082,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "-160",
	                "50",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4083,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_001",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4084,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4085,
	            "command": "play_sound",
	            "args": [
	                "SE_239"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4086,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4087,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4088,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "160",
	                "50",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4089,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_001",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4090,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4091,
	            "command": "elif",
	            "args": [
	                "WEAPON",
	                "AXE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4092,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_090",
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4093,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_090",
	                "0.75"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4094,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_090",
	                "2.0",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4095,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_090",
	                "150",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4096,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "150",
	                "50"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4097,
	            "command": "play_sound",
	            "args": [
	                "SE_116"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4098,
	            "command": "stop_se",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4099,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4100,
	            "command": "play_sound",
	            "args": [
	                "SE_116"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4101,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "0",
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4102,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4103,
	            "command": "stop_se",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4104,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4105,
	            "command": "play_sound",
	            "args": [
	                "SE_116"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4106,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "0",
	                "0",
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4107,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "-150",
	                "-50"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4108,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4109,
	            "command": "elif",
	            "args": [
	                "WEAPON",
	                "WIND"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4110,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_061"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4111,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_061",
	                "2.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4112,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4113,
	            "command": "play_sound",
	            "args": [
	                "SE_064"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4114,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4115,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4116,
	            "command": "if",
	            "args": [
	                "WEAPON",
	                "WIND"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4117,
	            "command": "c_face",
	            "args": [
	                "eye",
	                "lip",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4118,
	            "command": "c_face",
	            "args": [
	                "eye2",
	                "lip2",
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4119,
	            "command": "c_face",
	            "args": [
	                "eye3",
	                "lip3",
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4120,
	            "command": "chara_shake_h",
	            "args": [
	                "CID",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4121,
	            "command": "chara_shake_h",
	            "args": [
	                "CID2",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4122,
	            "command": "chara_shake_h",
	            "args": [
	                "CID3",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4123,
	            "command": "wait",
	            "args": [
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4124,
	            "command": "chara_shake_h",
	            "args": [
	                "CID",
	                "2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4125,
	            "command": "chara_shake_h",
	            "args": [
	                "CID2",
	                "2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4126,
	            "command": "chara_shake_h",
	            "args": [
	                "CID3",
	                "2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4127,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4128,
	            "command": "c_face",
	            "args": [
	                "eye",
	                "lip",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4129,
	            "command": "c_face",
	            "args": [
	                "eye2",
	                "lip2",
	                "CID2",
	                "int2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4130,
	            "command": "c_face",
	            "args": [
	                "eye3",
	                "lip3",
	                "CID3",
	                "int3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4131,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4132,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4133,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4134,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
