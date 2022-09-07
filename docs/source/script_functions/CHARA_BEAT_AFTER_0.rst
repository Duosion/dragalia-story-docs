.. _CHARA_BEAT_AFTER_0:

CHARA_BEAT_AFTER_0
========================

.. code-block:: text

	CHARA_BEAT_AFTER_0(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_AFTER_0",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4266,
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
	            "row": 4267,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4268,
	            "command": "play_sound",
	            "args": [
	                "SE_065"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4269,
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
	            "row": 4270,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4271,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`chara_fadeout`
* :ref:`play_sound`
* :ref:`effect_shake_bg`
* :ref:`wait`
* :ref:`RestartAll`
