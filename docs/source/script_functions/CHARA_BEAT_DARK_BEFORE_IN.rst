.. _CHARA_BEAT_DARK_BEFORE_IN:

CHARA_BEAT_DARK_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_DARK_BEFORE_IN(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	play_sound(SE_245)
	wait(0.3)
	set_BG_effect(EFF_039)
	wait(0.2)
	c_swing2_h_fast(CID)
	wait(0.25)

References
-------------
* :ref:`play_sound`
* :ref:`wait`
* :ref:`set_BG_effect`
* :ref:`c_swing2_h_fast`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_DARK_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4020,
	            "command": "play_sound",
	            "args": [
	                "SE_245"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4021,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4022,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_039"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4023,
	            "command": "wait",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4024,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4025,
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
