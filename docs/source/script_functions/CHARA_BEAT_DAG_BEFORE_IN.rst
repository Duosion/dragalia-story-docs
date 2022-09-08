.. _CHARA_BEAT_DAG_BEFORE_IN:

CHARA_BEAT_DAG_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_DAG_BEFORE_IN(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_BEAT_DAG_BEFORE_IN(CID):
		set_BG_effect(EFF_090)
		wait(0.1)
		play_sound(SE_236)
		c_swing2_h_fast(CID)
		wait(0.25)

References
-------------
* :ref:`set_BG_effect`
* :ref:`wait`
* :ref:`play_sound`
* :ref:`c_swing2_h_fast`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT_DAG_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3912,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_090"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3913,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3914,
	            "command": "play_sound",
	            "args": [
	                "SE_236"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3915,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3916,
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
