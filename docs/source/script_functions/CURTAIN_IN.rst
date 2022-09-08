.. _CURTAIN_IN:

CURTAIN_IN
========================

.. code-block:: text

	CURTAIN_IN()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CURTAIN_IN():
		set_BG_effect(EFF_107)
		set_BG_effect_trigger(9)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CURTAIN_IN",
	    "args": [],
	    "commandList": [
	        {
	            "row": 1684,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_107"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1685,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
