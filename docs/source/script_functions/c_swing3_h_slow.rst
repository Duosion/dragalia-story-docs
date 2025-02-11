.. _c_swing3_h_slow:

c_swing3_h_slow
========================

.. code-block:: text

	c_swing3_h_slow(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_swing3_h_slow(CID):
		mnu_move(CID, true, 0.5, 16, 0, 9)
		mnu_move(CID, false, 0.5, -32, 0, 9)
		mnu_move(CID, false, 0.5, 32, 0, 9)
		mnu_move(CID, false, 0.5, -32, 0, 9)
		mnu_move(CID, false, 0.5, 16, 0, 9)
		cmp_move(CID, 2.5, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_swing3_h_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4836,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.5",
	                "16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4837,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-32",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4838,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "32",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4839,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-32",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4840,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4841,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "2.5",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
