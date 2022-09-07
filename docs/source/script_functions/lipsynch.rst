.. _lipsynch:

lipsynch
========================

.. code-block:: text

	lipsynch(CID, lip)


Arguments
------------

* CID
* lip

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "lipsynch",
	    "args": [
	        "CID",
	        "lip"
	    ],
	    "commandList": [
	        {
	            "row": 5679,
	            "command": "if",
	            "args": [
	                "lip",
	                "O"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5680,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID",
	                "-2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5681,
	            "command": "elif",
	            "args": [
	                "lip",
	                "Q"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5682,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID",
	                "-1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5683,
	            "command": "elif",
	            "args": [
	                "lip",
	                "M"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5684,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5685,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5686,
	            "command": "chara_lipsynch",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5687,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`chara_lipsynch`
