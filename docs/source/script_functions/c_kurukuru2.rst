.. _c_kurukuru2:

c_kurukuru2
========================

.. code-block:: text

	c_kurukuru2(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_kurukuru2(CID):
		mnu_move(CID, true, 0.065, -10, 4.1, 1)
		mnu_move(CID, false, 0.065, -4.1, 10, 1)
		mnu_move(CID, false, 0.065, 4.1, 10, 1)
		mnu_move(CID, false, 0.065, 10, 4.1, 1)
		mnu_move(CID, false, 0.065, 10, -4.1, 1)
		mnu_move(CID, false, 0.065, 4.1, -10, 1)
		mnu_move(CID, false, 0.065, -4.1, -10, 1)
		mnu_move(CID, false, 0.065, -10, -4.1, 1)
		mnu_move(CID, false, 0.065, -10, 4.1, 1)
		mnu_move(CID, false, 0.065, -4.1, 10, 1)
		mnu_move(CID, false, 0.065, 4.1, 10, 1)
		mnu_move(CID, false, 0.065, 10, 4.1, 1)
		mnu_move(CID, false, 0.065, 10, -4.1, 1)
		mnu_move(CID, false, 0.065, 4.1, -10, 1)
		mnu_move(CID, false, 0.065, -4.1, -10, 1)
		mnu_move(CID, false, 0.065, -10, -4.1, 1)
		cmp_move(CID, 1.04, 0, 0)
		wait(0.0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
* :ref:`wait`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_kurukuru2",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5047,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.065",
	                "-10",
	                "4.1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5048,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "-4.1",
	                "10",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5049,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "4.1",
	                "10",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5050,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "10",
	                "4.1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5051,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "10",
	                "-4.1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5052,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "4.1",
	                "-10",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5053,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "-4.1",
	                "-10",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5054,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "-10",
	                "-4.1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5055,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "-10",
	                "4.1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5056,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "-4.1",
	                "10",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5057,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "4.1",
	                "10",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5058,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "10",
	                "4.1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5059,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "10",
	                "-4.1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5060,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "4.1",
	                "-10",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5061,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "-4.1",
	                "-10",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5062,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.065",
	                "-10",
	                "-4.1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5063,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.04",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5064,
	            "command": "wait",
	            "args": [
	                "0.0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
