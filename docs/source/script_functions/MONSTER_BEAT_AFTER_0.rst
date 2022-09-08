.. _MONSTER_BEAT_AFTER_0:

MONSTER_BEAT_AFTER_0
========================

.. code-block:: text

	MONSTER_BEAT_AFTER_0(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.6, 0, -150, EaseOutQuint)
	chara_fadeout(CID, 0.6)
	play_sound(SE_262)
	effect_shake_bg(12, 0.1, 0.2, 1)
	wait(0.5)
	RestartAll(CID)

References
-------------
* :ref:`mnu_move`
* :ref:`chara_fadeout`
* :ref:`play_sound`
* :ref:`effect_shake_bg`
* :ref:`wait`
* :ref:`RestartAll`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_BEAT_AFTER_0",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4275,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4276,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4277,
	            "command": "play_sound",
	            "args": [
	                "SE_262"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4278,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.1",
	                "0.2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4279,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4280,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
