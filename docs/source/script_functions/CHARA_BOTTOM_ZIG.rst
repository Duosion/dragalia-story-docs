.. _CHARA_BOTTOM_ZIG:

CHARA_BOTTOM_ZIG
========================

.. code-block:: text

	CHARA_BOTTOM_ZIG(eye, lip, POS, CID, int)


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

.. code-block:: json

	{
	    "name": "CHARA_BOTTOM_ZIG",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1799,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1800,
	            "command": "if",
	            "args": [
	                "POS",
	                "L"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1801,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "-200",
	                "-50"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1802,
	            "command": "elif",
	            "args": [
	                "POS",
	                "C"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1803,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "0",
	                "-50"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1804,
	            "command": "elif",
	            "args": [
	                "POS",
	                "R"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1805,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "200",
	                "-50"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1806,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1807,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1808,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1809,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1810,
	            "command": "BOTTOM_IN_ZIG",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`chara_face`
* :ref:`eye1`
* :ref:`lip1`
* :ref:`BOTTOM_IN_ZIG`
