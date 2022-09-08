.. _SHAKE_BG_LOOP:

SHAKE_BG_LOOP
========================

.. code-block:: text

	SHAKE_BG_LOOP(SHAKE_VALUE, PEEC_SEC)


Arguments
------------

* SHAKE_VALUE
* PEEC_SEC

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	effect_shake_bg(SHAKE_VALUE, PEEC_SEC, -1)

References
-------------
* :ref:`effect_shake_bg`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHAKE_BG_LOOP",
	    "args": [
	        "SHAKE_VALUE",
	        "PEEC_SEC"
	    ],
	    "commandList": [
	        {
	            "row": 5196,
	            "command": "effect_shake_bg",
	            "args": [
	                "SHAKE_VALUE",
	                "PEEC_SEC",
	                "-1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
