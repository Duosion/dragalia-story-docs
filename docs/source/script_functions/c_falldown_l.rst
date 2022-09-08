.. _c_falldown_l:

c_falldown_l
========================

.. code-block:: text

	c_falldown_l(CID, X, Y, SE)


Arguments
------------

* CID
* X
* Y
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_falldown_l(CID, X, Y, SE):
		mnu_move(CID, true, 0.2, -40, 50, EaseOutCubic)
		mnu(CID, false, 0.2, -40, -260, EaseInCubic, 0.2, 1, 1, 1, 0.2, 30, 1, 0.2, 1, 1)
		mnu_move(CID, false, 0.1, -20, 14, EaseOutCubic)
		mnu_move(CID, false, 0.1, -20, -4, EaseInCubic)
		cmp(CID, 0.6, -120, -200, 1, 1, -30, 1)
		wait(0.3)
		play_sound(SE_065)
		wait(0.1)
		StopEye_close(CID)
		set_BG_effect(EFF_001)
		set_BG_effect_pos(EFF_001, X, Y)
		wait(0.05)
		play_sound(SE)
		effect_shake_bg(12, 0.2, 1.0)

References
-------------
* :ref:`mnu_move`
* :ref:`mnu`
* :ref:`cmp`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`StopEye_close`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`effect_shake_bg`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_falldown_l",
	    "args": [
	        "CID",
	        "X",
	        "Y",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 5083,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "-40",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5084,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "-40",
	                "-260",
	                "EaseInCubic",
	                "0.2",
	                "1",
	                "1",
	                "1",
	                "0.2",
	                "30",
	                "1",
	                "0.2",
	                "1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5085,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "-20",
	                "14",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5086,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "-20",
	                "-4",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5087,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "0.6",
	                "-120",
	                "-200",
	                "1",
	                "1",
	                "-30",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5088,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5089,
	            "command": "play_sound",
	            "args": [
	                "SE_065"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5090,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5091,
	            "command": "StopEye_close",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5092,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_001"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5093,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_001",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5094,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5095,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5096,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.2",
	                "1.0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
