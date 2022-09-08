.. _SHAKE_CH_LOOP:

SHAKE_CH_LOOP
========================

.. code-block:: text

	SHAKE_CH_LOOP(SHAKE_VALUE, PEEC_SEC)


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

	effect_shake_chara(SHAKE_VALUE, PEEC_SEC, -1)

References
-------------
* :ref:`effect_shake_chara`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHAKE_CH_LOOP",
	    "args": [
	        "SHAKE_VALUE",
	        "PEEC_SEC"
	    ],
	    "commandList": [
	        {
	            "row": 5207,
	            "command": "effect_shake_chara",
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
