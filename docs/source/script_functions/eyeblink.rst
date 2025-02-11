.. _eyeblink:

eyeblink
========================

.. code-block:: text

	eyeblink(CID, eye)


Arguments
------------

* CID
* eye

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def eyeblink(CID, eye):
		if eye == "O":
			chara_eyeblink(CID, -1)
		elif eye == "Q":
			chara_eyeblink(CID, -2)
		elif eye == "M":
			chara_eyeblink(CID)
		else:
			chara_eyeblink(CID)

References
-------------
* :ref:`chara_eyeblink`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "eyeblink",
	    "args": [
	        "CID",
	        "eye"
	    ],
	    "commandList": [
	        {
	            "row": 5667,
	            "command": "if",
	            "args": [
	                "eye",
	                "O"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5668,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID",
	                "-1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5669,
	            "command": "elif",
	            "args": [
	                "eye",
	                "Q"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5670,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5671,
	            "command": "elif",
	            "args": [
	                "eye",
	                "M"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5672,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5673,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5674,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5675,
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
