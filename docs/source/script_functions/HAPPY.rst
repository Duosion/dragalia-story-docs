.. _HAPPY:

HAPPY
========================

.. code-block:: text

	HAPPY()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def HAPPY():
		play_sound(SE_170)
		set_BG_effect(EFF_094)

References
-------------
* :ref:`play_sound`
* :ref:`set_BG_effect`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "HAPPY",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3185,
	            "command": "play_sound",
	            "args": [
	                "SE_170"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3186,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_094"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
