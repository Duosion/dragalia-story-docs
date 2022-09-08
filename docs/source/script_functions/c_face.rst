.. _c_face:

c_face
========================

.. code-block:: text

	c_face(eye, lip, CID, int)


Arguments
------------

* eye
* lip
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_face(eye, lip, CID, int):
		eye1(CID, eye)
		lip1(CID, lip)
		chara_face(CID, int)

References
-------------
* :ref:`eye1`
* :ref:`lip1`
* :ref:`chara_face`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_face",
	    "args": [
	        "eye",
	        "lip",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 3016,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3017,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3018,
	            "command": "chara_face",
	            "args": [
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
