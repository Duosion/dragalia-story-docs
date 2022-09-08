.. _CHARA_SET_W:

CHARA_SET_W
========================

.. code-block:: text

	CHARA_SET_W(eye, lip, POS, CID, int, int2)


Arguments
------------

* eye
* lip
* POS
* CID
* int
* int2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	c_set_def(eye, lip, POS, CID, int)
	chara_face(CID, int2, 1)
	CHARA_FADEIN_DEF(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`chara_face`
* :ref:`CHARA_FADEIN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SET_W",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int",
	        "int2"
	    ],
	    "commandList": [
	        {
	            "row": 1727,
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
	            "row": 1728,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1729,
	            "command": "CHARA_FADEIN_DEF",
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
