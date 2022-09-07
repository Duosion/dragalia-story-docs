.. _CHARA_BEAT_MALIONE:

CHARA_BEAT_MALIONE
========================

.. code-block:: text

	CHARA_BEAT_MALIONE(CID, X, Y, R)


Arguments
------------

* CID
* X
* Y
* R

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_MALIONE",
	    "args": [
	        "CID",
	        "X",
	        "Y",
	        "R"
	    ],
	    "commandList": [
	        {
	            "row": 5611,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_SCE_2D_CMN_145"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5612,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5613,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1.3",
	                "0.25"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5614,
	            "command": "set_BG_effect_color",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "255",
	                "198",
	                "107"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5615,
	            "command": "set_BG_effect_rotation",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "R"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5616,
	            "command": "set_BG_effect_speed",
	            "args": [
	                "EFF_SCE_2D_CMN_145",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5617,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0012"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5618,
	            "command": "play_sound",
	            "args": [
	                "SE_STORY_COMMON_0234"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5619,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5620,
	            "command": "wait",
	            "args": [
	                "0.25"
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
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_scale`
* :ref:`set_BG_effect_color`
* :ref:`set_BG_effect_rotation`
* :ref:`set_BG_effect_speed`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`
* :ref:`wait`
