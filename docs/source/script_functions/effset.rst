.. _effset:

effset
========================

.. code-block:: text

	effset(effectIds, triggers)


Arguments
------------

* effectIds
* triggers

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def effset(effectIds, triggers):
		set_BG_effect(effectIds)
		set_BG_effect_trigger(triggers)

References
-------------
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "effset",
	    "args": [
	        "effectIds",
	        "triggers"
	    ],
	    "commandList": [
	        {
	            "row": 66,
	            "command": "set_BG_effect",
	            "args": [
	                "effectIds"
	            ],
	            "end": 1
	        },
	        {
	            "row": 67,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "triggers"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
