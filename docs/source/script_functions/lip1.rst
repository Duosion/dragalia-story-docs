.. _lip1:

lip1
========================

.. code-block:: text

	lip1(CID, lip)


Arguments
------------

* CID
* lip

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	if lip == O:
		chara_lipsynch(CID, -2)
	elif lip == Q:
		chara_lipsynch(CID, -1)
	elif lip == M:
		chara_lipsynch(CID)
	else:
		chara_lipsynch(CID)

References
-------------
* :ref:`chara_lipsynch`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "lip1",
	    "args": [
	        "CID",
	        "lip"
	    ],
	    "commandList": [
	        {
	            "row": 53,
	            "command": "if",
	            "args": [
	                "lip",
	                "O"
	            ],
	            "end": 1
	        },
	        {
	            "row": 54,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 55,
	            "command": "elif",
	            "args": [
	                "lip",
	                "Q"
	            ],
	            "end": 1
	        },
	        {
	            "row": 56,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID",
	                "-1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 57,
	            "command": "elif",
	            "args": [
	                "lip",
	                "M"
	            ],
	            "end": 1
	        },
	        {
	            "row": 58,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 59,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 60,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 61,
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
