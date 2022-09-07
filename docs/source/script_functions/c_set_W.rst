.. _c_set_W:

c_set_W
========================

.. code-block:: text

	c_set_W(act, cmd, eye, lip, POS, CID, int, int2)


Arguments
------------

* act
* cmd
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

.. code-block:: json

	{
	    "name": "c_set_W",
	    "args": [
	        "act",
	        "cmd",
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int",
	        "int2"
	    ],
	    "commandList": [
	        {
	            "row": 181,
	            "command": "if",
	            "args": [
	                "act",
	                "in"
	            ],
	            "end": 1
	        },
	        {
	            "row": 182,
	            "command": "if",
	            "args": [
	                "cmd",
	                "def"
	            ],
	            "end": 1
	        },
	        {
	            "row": 183,
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
	            "row": 184,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 185,
	            "command": "CHARA_FADEIN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 186,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 187,
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

References
-------------
* :ref:`c_set_def`
* :ref:`chara_face`
* :ref:`CHARA_FADEIN_DEF`
