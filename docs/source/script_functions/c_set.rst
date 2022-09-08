.. _c_set:

c_set
========================

.. code-block:: text

	c_set(act, cmd, eye, lip, POS, CID, int)


Arguments
------------

* act
* cmd
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

	def c_set(act, cmd, eye, lip, POS, CID, int):
		if act == "in":
		if cmd == "def":
			c_set_def(eye, lip, POS, CID, int)
			CHARA_FADEIN_DEF(CID)
		elif cmd == "kami":
			c_set_def(eye, lip, POS, CID, int)
			KAMITE_IN_DEF(CID)

References
-------------
* :ref:`c_set_def`
* :ref:`CHARA_FADEIN_DEF`
* :ref:`KAMITE_IN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_set",
	    "args": [
	        "act",
	        "cmd",
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 193,
	            "command": "if",
	            "args": [
	                "act",
	                "in"
	            ],
	            "end": 1
	        },
	        {
	            "row": 194,
	            "command": "if",
	            "args": [
	                "cmd",
	                "def"
	            ],
	            "end": 1
	        },
	        {
	            "row": 195,
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
	            "row": 196,
	            "command": "CHARA_FADEIN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 197,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "kami"
	            ],
	            "end": 1
	        },
	        {
	            "row": 198,
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
	            "row": 199,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 200,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 201,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
