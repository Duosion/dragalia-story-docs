.. _CHARA_FROM_ANOTHER_WORLD:

CHARA_FROM_ANOTHER_WORLD
========================

.. code-block:: text

	CHARA_FROM_ANOTHER_WORLD(eye, lip, X, Y, CID, Face, MinScale, MaxScale, Type, Aura)


Arguments
------------

* eye
* lip
* X
* Y
* CID
* Face
* MinScale
* MaxScale
* Type
* Aura

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_FROM_ANOTHER_WORLD(eye, lip, X, Y, CID, Face, MinScale, MaxScale, Type, Aura):
		c_mnu_reset(CID)
		touch_enable(false)
		if Type == "Enemy":
			play_sound(SE_011)
			set_BG_effect(EFF_SCE_2D_CMN_046)
			wait(0.5)
		else:
		CHARA_SET_POS_0(eye, lip, X, Y, CID, Face)
		mnu_scale(CID, true, 0.01, MinScale, MinScale, 1)
		cmp_scale(CID, 0.01, MinScale, MinScale)
		play_sound(SE_057)
		if Type == "Enemy":
			set_BG_effect(1, EFF_SCE_2D_CMN_004)
		elif Type == "Chara":
			set_BG_effect(EFF_SCE_2D_CMN_004)
		set_BG_effect_opacity(EFF_SCE_2D_CMN_004, 1)
		set_BG_effect_scale(EFF_SCE_2D_CMN_004, 1, 1)
		set_BG_effect_pos(EFF_SCE_2D_CMN_004, 0, 100)
		if Type == "Enemy":
			set_BG_effect_trigger(0, 8)
		elif Type == "Chara":
			set_BG_effect_trigger(8)
		wait(1.4)
		if Type == "Chara":
			mnu(CID, true, 0.8, 0, 0, EaseInSine, 0.8, MaxScale, MaxScale, EaseInSine, 0.8, 0, EaseInSine, 0.4, 1, EaseInSine)
			cmp(CID, 0.8, 0, 0, MaxScale, MaxScale, 0, 1)
			set_BG_effect_opacity(EFF_SCE_2D_CMN_004, 0, 1.6, 1)
			wait(0.8)
			set_BG_effect_scale(EFF_SCE_2D_CMN_004, 0.01, 0.01, 0.8, 1)
			wait(0.8)
			set_BG_effect(0, 1, 1, 1)
		elif Type == "Enemy":
			mnu(CID, true, 0.8, 0, 0, EaseInSine, 0.8, MaxScale, MaxScale, EaseInSine, 0.8, 0, EaseInSine, 0.4, 1, EaseInSine)
			cmp(CID, 0.8, 0, 0, MaxScale, MaxScale, 0, 1)
		else:
		if Aura == "1":
			set_BG_effect(1, 1, EFF_SCE_2D_CMN_010, EFF_SCE_2D_CMN_011)
			set_BG_effect_scale(EFF_SCE_2D_CMN_010, MaxScale, MaxScale)
			set_BG_effect_scale(EFF_SCE_2D_CMN_011, MaxScale, MaxScale)
			set_BG_effect_pos(EFF_SCE_2D_CMN_010, X, Y)
			set_BG_effect_pos(EFF_SCE_2D_CMN_011, X, Y)
			set_BG_effect_trigger(0, 0, 8, 8)
		chara_visible(CID, true)
		touch_enable(true)

References
-------------
* :ref:`c_mnu_reset`
* :ref:`touch_enable`
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`wait`
* :ref:`CHARA_SET_POS_0`
* :ref:`mnu_scale`
* :ref:`cmp_scale`
* :ref:`set_BG_effect_opacity`
* :ref:`set_BG_effect_scale`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_trigger`
* :ref:`mnu`
* :ref:`cmp`
* :ref:`chara_visible`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_FROM_ANOTHER_WORLD",
	    "args": [
	        "eye",
	        "lip",
	        "X",
	        "Y",
	        "CID",
	        "Face",
	        "MinScale",
	        "MaxScale",
	        "Type",
	        "Aura"
	    ],
	    "commandList": [
	        {
	            "row": 5420,
	            "command": "c_mnu_reset",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5421,
	            "command": "touch_enable",
	            "args": [
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5422,
	            "command": "if",
	            "args": [
	                "Type",
	                "Enemy"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5423,
	            "command": "play_sound",
	            "args": [
	                "SE_011"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5424,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_046"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5425,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5426,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5427,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5428,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "eye",
	                "lip",
	                "X",
	                "Y",
	                "CID",
	                "Face"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5429,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "true",
	                "0.01",
	                "MinScale",
	                "MinScale",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5430,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.01",
	                "MinScale",
	                "MinScale"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5431,
	            "command": "play_sound",
	            "args": [
	                "SE_057"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5432,
	            "command": "if",
	            "args": [
	                "Type",
	                "Enemy"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5433,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "EFF_SCE_2D_CMN_004"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5434,
	            "command": "elif",
	            "args": [
	                "Type",
	                "Chara"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5435,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_004"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5436,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5437,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_SCE_2D_CMN_004",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5438,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_004",
	                "1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5439,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_SCE_2D_CMN_004",
	                "0",
	                "100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5440,
	            "command": "if",
	            "args": [
	                "Type",
	                "Enemy"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5441,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "0",
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5442,
	            "command": "elif",
	            "args": [
	                "Type",
	                "Chara"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5443,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5444,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5445,
	            "command": "wait",
	            "args": [
	                "1.4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5446,
	            "command": "if",
	            "args": [
	                "Type",
	                "Chara"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5447,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "0",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "MaxScale",
	                "MaxScale",
	                "EaseInSine",
	                "0.8",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5448,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "0.8",
	                "0",
	                "0",
	                "MaxScale",
	                "MaxScale",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5449,
	            "command": "set_BG_effect_opacity",
	            "args": [
	                "EFF_SCE_2D_CMN_004",
	                "0",
	                "1.6",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5450,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5451,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_004",
	                "0.01",
	                "0.01",
	                "0.8",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5452,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5453,
	            "command": "set_BG_effect",
	            "args": [
	                "0",
	                "1",
	                "1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5454,
	            "command": "elif",
	            "args": [
	                "Type",
	                "Enemy"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5455,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "0",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "MaxScale",
	                "MaxScale",
	                "EaseInSine",
	                "0.8",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "EaseInSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5456,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "0.8",
	                "0",
	                "0",
	                "MaxScale",
	                "MaxScale",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5457,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5458,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5459,
	            "command": "if",
	            "args": [
	                "Aura",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5460,
	            "command": "set_BG_effect",
	            "args": [
	                "1",
	                "1",
	                "EFF_SCE_2D_CMN_010",
	                "EFF_SCE_2D_CMN_011"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5461,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_010",
	                "MaxScale",
	                "MaxScale"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5462,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_011",
	                "MaxScale",
	                "MaxScale"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5463,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_SCE_2D_CMN_010",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5464,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_SCE_2D_CMN_011",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5465,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "0",
	                "0",
	                "8",
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5466,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5467,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5468,
	            "command": "touch_enable",
	            "args": [
	                "true"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
