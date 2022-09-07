.. _ARTICLE_STONE:

ARTICLE_STONE
========================

.. code-block:: text

	ARTICLE_STONE(EFF)


Arguments
------------

* EFF

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "ARTICLE_STONE",
	    "args": [
	        "EFF"
	    ],
	    "commandList": [
	        {
	            "row": 3110,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3111,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3112,
	            "command": "play_sound",
	            "args": [
	                "SE_139"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3113,
	            "command": "play_sound",
	            "args": [
	                "SE_140"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3114,
	            "command": "if",
	            "args": [
	                "EFF",
	                "EFF_022"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3115,
	            "command": "set_BG_effect",
	            "args": [
	                "0",
	                "EFF_025"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3116,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_025",
	                "0",
	                "100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3117,
	            "command": "elif",
	            "args": [
	                "EFF",
	                "EFF_023"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3118,
	            "command": "set_BG_effect",
	            "args": [
	                "0",
	                "EFF_026"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3119,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_026",
	                "0",
	                "100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3120,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3121,
	            "command": "fade_color",
	            "args": [
	                "0.8",
	                "255",
	                "255",
	                "255",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3122,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3123,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF",
	                "0",
	                "100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3124,
	            "command": "fade_color",
	            "args": [
	                "3.0",
	                "255",
	                "255",
	                "255",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3125,
	            "command": "touch_wait",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3126,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3127,
	            "command": "SEFOUT_DEF",
	            "args": [],
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
* :ref:`SCREEN_FLASH_WHITE_DEF`
* :ref:`WFOUT_DEF`
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`fade_color`
* :ref:`touch_wait`
* :ref:`NO_EFFECT`
* :ref:`SEFOUT_DEF`
