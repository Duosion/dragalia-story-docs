.. _YORU_LIGHT:

YORU_LIGHT
========================

.. code-block:: text

	YORU_LIGHT(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	chara_color(CID, 0, 3, 44, 122, 156, 1, -0.25, 0.67)
	wait(0)

References
-------------
* :ref:`chara_color`
* :ref:`wait`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "YORU_LIGHT",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4489,
	            "command": "chara_color",
	            "args": [
	                "CID",
	                "0",
	                "3",
	                "44",
	                "122",
	                "156",
	                "1",
	                "-0.25",
	                "0.67"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4490,
	            "command": "wait",
	            "args": [
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
