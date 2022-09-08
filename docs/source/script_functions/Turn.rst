.. _Turn:

Turn
========================

.. code-block:: text

	Turn(CID, LR)


Arguments
------------

* CID
* LR

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	if LR == L:
		mnu(CID, true, 0.2, 50, 0, EaseInSine, 0.4, 1.02, 1.02, EaseInSine, 0.2, 0, EaseInSine, 0.2, 1, EaseInCubic)
		mnu(CID, false, 0.4, -100, 0, EaseOutSine, 0.4, 1.0, 1.0, EaseOutSine, 0.4, 0, EaseInSine, 0.4, 1, EaseInCubic)
		mnu(CID, false, 0.2, 50, 0, EaseInSine, 0, 1.0, 1.0, EaseInSine, 0.2, 0, EaseInSine, 0.2, 1, EaseInCubic)
		cmp(CID, 0.8, 0, 0, 1, 1, 0, 1)
	elif LR == R:
		mnu(CID, true, 0.2, -50, 0, EaseInSine, 0.4, 0.95, 0.95, EaseInSine, 0.2, 0, EaseInSine, 0.2, 1, EaseInCubic)
		mnu(CID, false, 0.4, 100, 0, EaseOutSine, 0.4, 1.0, 1.0, EaseOutSine, 0.4, 0, EaseInSine, 0.4, 1, EaseInCubic)
		mnu(CID, false, 0.2, -50, 0, EaseInSine, 0, 1.0, 1.0, EaseInSine, 0.2, 0, EaseInSine, 0.2, 1, EaseInCubic)
		cmp(CID, 0.8, 0, 0, 1, 1, 0, 1)

References
-------------
* :ref:`mnu`
* :ref:`cmp`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "Turn",
	    "args": [
	        "CID",
	        "LR"
	    ],
	    "commandList": [
	        {
	            "row": 6226,
	            "command": "if",
	            "args": [
	                "LR",
	                "L"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6227,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "50",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1.02",
	                "1.02",
	                "EaseInSine",
	                "0.2",
	                "0",
	                "EaseInSine",
	                "0.2",
	                "1",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6228,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "false",
	                "0.4",
	                "-100",
	                "0",
	                "EaseOutSine",
	                "0.4",
	                "1.0",
	                "1.0",
	                "EaseOutSine",
	                "0.4",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6229,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "50",
	                "0",
	                "EaseInSine",
	                "0",
	                "1.0",
	                "1.0",
	                "EaseInSine",
	                "0.2",
	                "0",
	                "EaseInSine",
	                "0.2",
	                "1",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6230,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "0.8",
	                "0",
	                "0",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6231,
	            "command": "elif",
	            "args": [
	                "LR",
	                "R"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6232,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "-50",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "0.95",
	                "0.95",
	                "EaseInSine",
	                "0.2",
	                "0",
	                "EaseInSine",
	                "0.2",
	                "1",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6233,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "false",
	                "0.4",
	                "100",
	                "0",
	                "EaseOutSine",
	                "0.4",
	                "1.0",
	                "1.0",
	                "EaseOutSine",
	                "0.4",
	                "0",
	                "EaseInSine",
	                "0.4",
	                "1",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6234,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "-50",
	                "0",
	                "EaseInSine",
	                "0",
	                "1.0",
	                "1.0",
	                "EaseInSine",
	                "0.2",
	                "0",
	                "EaseInSine",
	                "0.2",
	                "1",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6235,
	            "command": "cmp",
	            "args": [
	                "CID",
	                "0.8",
	                "0",
	                "0",
	                "1",
	                "1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6236,
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
