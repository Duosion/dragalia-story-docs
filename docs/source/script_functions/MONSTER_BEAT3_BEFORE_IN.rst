.. _MONSTER_BEAT3_BEFORE_IN:

MONSTER_BEAT3_BEFORE_IN
========================

.. code-block:: text

	MONSTER_BEAT3_BEFORE_IN(WEAPON, CID, CID2, CID3)


Arguments
------------

* WEAPON
* CID
* CID2
* CID3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_BEAT3_BEFORE_IN",
	    "args": [
	        "WEAPON",
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 4138,
	            "command": "if",
	            "args": [
	                "WEAPON",
	                "BOW"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4139,
	            "command": "play_sound",
	            "args": [
	                "SE_239"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4140,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_092"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4141,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4142,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_092",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4143,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4144,
	            "command": "play_sound",
	            "args": [
	                "SE_239"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4145,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4146,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "200",
	                "150"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4147,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_001",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4148,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_001",
	                "0.8",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4149,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4150,
	            "command": "play_sound",
	            "args": [
	                "SE_239"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4151,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4152,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4153,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "-200",
	                "150"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4154,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_001",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4155,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_001",
	                "0.8",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4156,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4157,
	            "command": "elif",
	            "args": [
	                "WEAPON",
	                "AXE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4158,
	            "command": "play_sound",
	            "args": [
	                "SE_116"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4159,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_093"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4160,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4161,
	            "command": "play_sound",
	            "args": [
	                "SE_116"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4162,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4163,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "200",
	                "150"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4164,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_001",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4165,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_001",
	                "0.8",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4166,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4167,
	            "command": "play_sound",
	            "args": [
	                "SE_116"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4168,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4169,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4170,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "-200",
	                "150"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4171,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_001",
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4172,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_001",
	                "0.8",
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4173,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4174,
	            "command": "if",
	            "args": [
	                "WEAPON",
	                "WATER"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4175,
	            "command": "play_sound",
	            "args": [
	                "SE_243"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4176,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4177,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_036"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4178,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4179,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4180,
	            "command": "elif",
	            "args": [
	                "WEAPON",
	                "WIND"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4181,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_061"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4182,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_061",
	                "2.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4183,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4184,
	            "command": "play_sound",
	            "args": [
	                "SE_064"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4185,
	            "command": "wait",
	            "args": [
	                "0.15"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4186,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4187,
	            "command": "if",
	            "args": [
	                "WEAPON",
	                "WIND"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4188,
	            "command": "chara_shake_h",
	            "args": [
	                "CID",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4189,
	            "command": "chara_shake_h",
	            "args": [
	                "CID2",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4190,
	            "command": "chara_shake_h",
	            "args": [
	                "CID3",
	                "2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4191,
	            "command": "wait",
	            "args": [
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4192,
	            "command": "chara_shake_h",
	            "args": [
	                "CID",
	                "2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4193,
	            "command": "chara_shake_h",
	            "args": [
	                "CID2",
	                "2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4194,
	            "command": "chara_shake_h",
	            "args": [
	                "CID3",
	                "2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4195,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4196,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4197,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4198,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4199,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`set_BG_effect_speed`
* :ref:`wait`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_scale`
* :ref:`NO_EFFECT`
* :ref:`chara_shake_h`
* :ref:`c_swing2_h_fast`
