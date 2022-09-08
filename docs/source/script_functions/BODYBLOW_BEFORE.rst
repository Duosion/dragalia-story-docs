.. _BODYBLOW_BEFORE:

BODYBLOW_BEFORE
========================

.. code-block:: text

	BODYBLOW_BEFORE(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def BODYBLOW_BEFORE(CID):
		set_BG_effect(0, 0, 0, EFF_091)
		play_sound(SE_232)
		wait(0.1)
		mnu_move(CID, true, 0.2, 0, 180, EaseOutQuint)
		mnu_move(CID, false, 0.02, 0, 0, 1)
		mnu_move(CID, false, 0.2, 0, -180, EaseInQuint)
		cmp_move(CID, 0.42, 0, 0)

References
-------------
* :ref:`set_BG_effect`
* :ref:`play_sound`
* :ref:`wait`
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "BODYBLOW_BEFORE",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4065,
	            "command": "set_BG_effect",
	            "args": [
	                "0",
	                "0",
	                "0",
	                "EFF_091"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4066,
	            "command": "play_sound",
	            "args": [
	                "SE_232"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4067,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4068,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "180",
	                "EaseOutQuint"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4069,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.02",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4070,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-180",
	                "EaseInQuint"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4071,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.42",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
