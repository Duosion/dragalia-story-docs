.. _THUNDER_SHAKE:

THUNDER_SHAKE
========================

.. code-block:: text

	THUNDER_SHAKE()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	wait(0.5)
	SCREEN_FLASH_WHITE_DEF()
	wait(0.2)
	SCREEN_FLASH_WHITE_DEF()
	fade_color(0.1, 255, 255, 255, 1)
	play_sound(SE_078)
	fade_color(0.8, 255, 255, 255, 0.5)
	play_sound(SE_007)
	fade_color(0.3, 255, 255, 255, 0.125)
	set_volume(0, 2.0, SE_007)
	fade_color(0.1, 255, 255, 255, 0)
	effect_shake_bg(1, 0.5, 1.0)
	wait(0.5)

References
-------------
* :ref:`wait`
* :ref:`SCREEN_FLASH_WHITE_DEF`
* :ref:`fade_color`
* :ref:`play_sound`
* :ref:`set_volume`
* :ref:`effect_shake_bg`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "THUNDER_SHAKE",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3157,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3158,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3159,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3160,
	            "command": "SCREEN_FLASH_WHITE_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3161,
	            "command": "fade_color",
	            "args": [
	                "0.1",
	                "255",
	                "255",
	                "255",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3162,
	            "command": "play_sound",
	            "args": [
	                "SE_078"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3163,
	            "command": "fade_color",
	            "args": [
	                "0.8",
	                "255",
	                "255",
	                "255",
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3164,
	            "command": "play_sound",
	            "args": [
	                "SE_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3165,
	            "command": "fade_color",
	            "args": [
	                "0.3",
	                "255",
	                "255",
	                "255",
	                "0.125"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3166,
	            "command": "set_volume",
	            "args": [
	                "0",
	                "2.0",
	                "SE_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3167,
	            "command": "fade_color",
	            "args": [
	                "0.1",
	                "255",
	                "255",
	                "255",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3168,
	            "command": "effect_shake_bg",
	            "args": [
	                "1",
	                "0.5",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3169,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
