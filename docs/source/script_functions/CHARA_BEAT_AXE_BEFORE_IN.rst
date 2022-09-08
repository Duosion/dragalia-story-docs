.. _CHARA_BEAT_AXE_BEFORE_IN:

CHARA_BEAT_AXE_BEFORE_IN
========================

.. code-block:: text

	CHARA_BEAT_AXE_BEFORE_IN(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	set_BG_effect(EFF_093)
	wait(0.1)
	play_sound(SE_116)
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
	    "name": "CHARA_BEAT_AXE_BEFORE_IN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3930,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_093"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3931,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3932,
	            "command": "play_sound",
	            "args": [
	                "SE_116"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3933,
	            "command": "c_swing2_h_fast",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3934,
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
