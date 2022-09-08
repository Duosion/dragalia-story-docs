.. _cmp_fade:

cmp_fade
========================

.. code-block:: text

	cmp_fade(CID, sec, fade)


Arguments
------------

* CID
* sec
* fade

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	chara_act_complete(CID, sec, -1.0, -1.0, -1.0, -1.0, -1.0, fade)

References
-------------
* :ref:`chara_act_complete`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "cmp_fade",
	    "args": [
	        "CID",
	        "sec",
	        "fade"
	    ],
	    "commandList": [
	        {
	            "row": 4594,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "sec",
	                "-1.0",
	                "-1.0",
	                "-1.0",
	                "-1.0",
	                "-1.0",
	                "fade"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
