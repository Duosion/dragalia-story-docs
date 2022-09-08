.. _c_swing_h_slow:

c_swing_h_slow
========================

.. code-block:: text

	c_swing_h_slow(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.5, 16, 0, 9)
	mnu_move(CID, false, 0.5, -32, 0, 9)
	mnu_move(CID, false, 0.5, 16, 0, 9)
	cmp_move(CID, 1.5, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_swing_h_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4821,
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
	            "row": 4822,
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
	            "row": 4823,
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
	            "row": 4824,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.5",
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
