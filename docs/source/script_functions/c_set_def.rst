.. _c_set_def:

c_set_def
========================

.. code-block:: text

	c_set_def(eye, lip, POS, CID, int)


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

	def c_set_def(eye, lip, POS, CID, int):
		CHARA_SET_0(eye, lip, POS, CID, int)

References
-------------
* :ref:`CHARA_SET_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_set_def",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 174,
	            "command": "CHARA_SET_0",
	            "args": [
	                "eye",
	                "lip",
	                "POS",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
