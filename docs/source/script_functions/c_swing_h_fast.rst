.. _c_swing_h_fast:

c_swing_h_fast
========================

.. code-block:: text

	c_swing_h_fast(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_swing_h_fast(CID):
		mnu_move(CID, true, 0.1, 10, 0, 9)
		mnu_move(CID, false, 0.1, -20, 0, 9)
		mnu_move(CID, false, 0.1, 10, 0, 9)
		cmp_move(CID, 0.3, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_swing_h_fast",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4859,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.1",
	                "10",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4860,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "-20",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4861,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "10",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4862,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
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
