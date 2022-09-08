.. _KIRA:

KIRA
========================

.. code-block:: text

	KIRA(posX, posY, scaleX, scaleY)


Arguments
------------

* posX
* posY
* scaleX
* scaleY

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def KIRA(posX, posY, scaleX, scaleY):
		play_sound(SE_256)
		set_BG_effect(EFF_015)
		set_BG_effect_pos(EFF_015, posX, posY)
		set_BG_effect_scale(EFF_015, scaleX, scaleY)

References
-------------
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_scale`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "KIRA",
	    "args": [
	        "posX",
	        "posY",
	        "scaleX",
	        "scaleY"
	    ],
	    "commandList": [
	        {
	            "row": 3190,
	            "command": "play_sound",
	            "args": [
	                "SE_256"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3191,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_015"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3192,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_015",
	                "posX",
	                "posY"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3193,
	            "command": "set_BG_effect_scale",
	            "args": [
	                "EFF_015",
	                "scaleX",
	                "scaleY"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
