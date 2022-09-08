.. _TEAR:

TEAR
========================

.. code-block:: text

	TEAR()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	touch_enable(false)
	play_sound(SE_057)
	set_BG_effect(EFF_004)
	set_BG_effect_pos(EFF_004, 0, 100)
	set_BG_effect_trigger(8)
	wait(2.5)
	touch_enable(true)
	touch_wait()
	SEFOUT_DEF()

References
-------------
* :ref:`touch_enable`
* :ref:`play_sound`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_pos`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
* :ref:`touch_wait`
* :ref:`SEFOUT_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "TEAR",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3173,
	            "command": "touch_enable",
	            "args": [
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3174,
	            "command": "play_sound",
	            "args": [
	                "SE_057"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3175,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_004"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3176,
	            "command": "set_BG_effect_pos",
	            "args": [
	                "EFF_004",
	                "0",
	                "100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3177,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3178,
	            "command": "wait",
	            "args": [
	                "2.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3179,
	            "command": "touch_enable",
	            "args": [
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3180,
	            "command": "touch_wait",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3181,
	            "command": "SEFOUT_DEF",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
