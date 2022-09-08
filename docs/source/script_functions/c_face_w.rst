.. _c_face_w:

c_face_w
========================

.. code-block:: text

	c_face_w(eye, lip, CID, int, int2)


Arguments
------------

* eye
* lip
* CID
* int
* int2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_face_w(eye, lip, CID, int, int2):
		c_face(eye, lip, CID, int)
		chara_face(CID, int2, 1)

References
-------------
* :ref:`c_face`
* :ref:`chara_face`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_face_w",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int",
	        "int2"
	    ],
	    "commandList": [
	        {
	            "row": 3021,
	            "command": "c_face",
	            "args": [
	                "eye",
	                "lip",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3022,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int2",
	                "1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
