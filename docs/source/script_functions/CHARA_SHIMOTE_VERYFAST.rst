.. _CHARA_SHIMOTE_VERYFAST:

CHARA_SHIMOTE_VERYFAST
========================

.. code-block:: text

	CHARA_SHIMOTE_VERYFAST(eye, lip, POS, CID, int)


Arguments
------------

* eye
* lip
* POS
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	c_set_def(eye, lip, POS, CID, int)
	SHIMOTE_IN_VERYFAST(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`SHIMOTE_IN_VERYFAST`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SHIMOTE_VERYFAST",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1768,
	            "command": "c_set_def",
	            "args": [
	                "eye",
	                "lip",
	                "POS",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1769,
	            "command": "SHIMOTE_IN_VERYFAST",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
