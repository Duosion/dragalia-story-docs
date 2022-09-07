.. _CHARA_EMO:

CHARA_EMO
========================

.. code-block:: text

	CHARA_EMO(CID, EID, FID)


Arguments
------------

* CID
* EID
* FID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_EMO",
	    "args": [
	        "CID",
	        "EID",
	        "FID"
	    ],
	    "commandList": [
	        {
	            "row": 4362,
	            "command": "if",
	            "args": [
	                "EID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4363,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "30.0",
	                "50.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4364,
	            "command": "elif",
	            "args": [
	                "EID",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4365,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "0.0",
	                "10.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4366,
	            "command": "elif",
	            "args": [
	                "EID",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4367,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "-250.0",
	                "80.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4368,
	            "command": "elif",
	            "args": [
	                "EID",
	                "4"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4369,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "-250.0",
	                "80.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4370,
	            "command": "elif",
	            "args": [
	                "EID",
	                "5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4371,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "-260.0",
	                "30.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4372,
	            "command": "elif",
	            "args": [
	                "EID",
	                "6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4373,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "-260.0",
	                "30.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4374,
	            "command": "elif",
	            "args": [
	                "EID",
	                "7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4375,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "-220.0",
	                "20.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4376,
	            "command": "elif",
	            "args": [
	                "EID",
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4377,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "-210.0",
	                "30.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4378,
	            "command": "elif",
	            "args": [
	                "EID",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4379,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "-260.0",
	                "0.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4380,
	            "command": "elif",
	            "args": [
	                "EID",
	                "10"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4381,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "-250.0",
	                "60.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4382,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4383,
	            "command": "chara_emotion",
	            "args": [
	                "CID",
	                "EID",
	                "FID",
	                "0.0",
	                "0.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4384,
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
* :ref:`chara_emotion`
