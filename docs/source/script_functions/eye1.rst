.. _eye1:

eye1
========================

.. code-block:: text

	eye1(CID, eye)


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

	if eye == O:
		chara_eyeblink(CID, -1)
	elif eye == Q:
		chara_eyeblink(CID, -2)
	elif eye == M:
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
	    "name": "eye1",
	    "args": [
	        "CID",
	        "eye"
	    ],
	    "commandList": [
	        {
	            "row": 40,
	            "command": "if",
	            "args": [
	                "eye",
	                "O"
	            ],
	            "end": 1
	        },
	        {
	            "row": 41,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID",
	                "-1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 42,
	            "command": "elif",
	            "args": [
	                "eye",
	                "Q"
	            ],
	            "end": 1
	        },
	        {
	            "row": 43,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 44,
	            "command": "elif",
	            "args": [
	                "eye",
	                "M"
	            ],
	            "end": 1
	        },
	        {
	            "row": 45,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 46,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 47,
	            "command": "chara_eyeblink",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 48,
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
