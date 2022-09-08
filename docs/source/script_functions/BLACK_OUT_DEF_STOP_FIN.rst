.. _BLACK_OUT_DEF_STOP_FIN:

BLACK_OUT_DEF_STOP_FIN
========================

.. code-block:: text

	BLACK_OUT_DEF_STOP_FIN(mode)


Arguments
------------

* mode

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	RESET_TEXT()
	if mode == 1:
		NO_EFFECT()
		touch_enable(false)
		window_fadeout(0, true)
		wait(0.5)
		fade_color(1.0, 0, 0, 0, 0.7, EaseLinear, true)
		wait(1.0)
		play_sound(SE_112)
		fin(true, 0, 170)
		set_BG_effect(EFF_125)
		touch_wait(0.5, 3.0)
		BGMFOUT_DEF()
		SEFOUT_DEF()
		fade_color(1.0, 0, 0, 0, 1)
	elif mode == 2:
		NO_EFFECT()
		touch_enable(false)
		wait(1.5)
		play_sound(SE_112)
		fin(true, 0, 170)
		set_BG_effect(EFF_125)
		touch_wait(0.5, 3.0)
		BGMFOUT_DEF()
		SEFOUT_DEF()
		fade_color(1.0, 0, 0, 0, 1)
	elif mode == 3:
		NO_EFFECT()
		touch_enable(false)
		window_fadeout(0, true)
		wait(1.5)
		play_sound(SE_112)
		fin(true, 0, 170)
		set_BG_effect(EFF_125)
		touch_wait(0.5, 3.0)
		BGMFOUT_DEF()
		SEFOUT_DEF()
		fade_color(1.0, 0, 0, 0, 1)

References
-------------
* :ref:`RESET_TEXT`
* :ref:`NO_EFFECT`
* :ref:`touch_enable`
* :ref:`window_fadeout`
* :ref:`wait`
* :ref:`fade_color`
* :ref:`play_sound`
* :ref:`fin`
* :ref:`set_BG_effect`
* :ref:`touch_wait`
* :ref:`BGMFOUT_DEF`
* :ref:`SEFOUT_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "BLACK_OUT_DEF_STOP_FIN",
	    "args": [
	        "mode"
	    ],
	    "commandList": [
	        {
	            "row": 1586,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1587,
	            "command": "if",
	            "args": [
	                "mode",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1588,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1589,
	            "command": "touch_enable",
	            "args": [
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1590,
	            "command": "window_fadeout",
	            "args": [
	                "0",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1591,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1592,
	            "command": "fade_color",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0",
	                "0.7",
	                "EaseLinear",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1593,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1594,
	            "command": "play_sound",
	            "args": [
	                "SE_112"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1595,
	            "command": "fin",
	            "args": [
	                "true",
	                "0",
	                "170"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1596,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_125"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1597,
	            "command": "touch_wait",
	            "args": [
	                "0.5",
	                "3.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1598,
	            "command": "BGMFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1599,
	            "command": "SEFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1600,
	            "command": "fade_color",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1601,
	            "command": "elif",
	            "args": [
	                "mode",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1602,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1603,
	            "command": "touch_enable",
	            "args": [
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1604,
	            "command": "wait",
	            "args": [
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1605,
	            "command": "play_sound",
	            "args": [
	                "SE_112"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1606,
	            "command": "fin",
	            "args": [
	                "true",
	                "0",
	                "170"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1607,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_125"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1608,
	            "command": "touch_wait",
	            "args": [
	                "0.5",
	                "3.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1609,
	            "command": "BGMFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1610,
	            "command": "SEFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1611,
	            "command": "fade_color",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1612,
	            "command": "elif",
	            "args": [
	                "mode",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1613,
	            "command": "NO_EFFECT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1614,
	            "command": "touch_enable",
	            "args": [
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1615,
	            "command": "window_fadeout",
	            "args": [
	                "0",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1616,
	            "command": "wait",
	            "args": [
	                "1.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1617,
	            "command": "play_sound",
	            "args": [
	                "SE_112"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1618,
	            "command": "fin",
	            "args": [
	                "true",
	                "0",
	                "170"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1619,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_125"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1620,
	            "command": "touch_wait",
	            "args": [
	                "0.5",
	                "3.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1621,
	            "command": "BGMFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1622,
	            "command": "SEFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1623,
	            "command": "fade_color",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1624,
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
