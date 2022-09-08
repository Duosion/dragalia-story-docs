.. _c_jump3:

c_jump3
========================

.. code-block:: text

	c_jump3(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.2, 0, 50, EaseOutCubic)
	mnu_move(CID, false, 0.2, 0, -60, EaseInCubic)
	mnu_move(CID, false, 0.2, 0, 60, EaseOutCubic)
	mnu_move(CID, false, 0.2, 0, -60, EaseInCubic)
	mnu_move(CID, false, 0.2, 0, 60, EaseOutCubic)
	mnu_move(CID, false, 0.2, 0, -60, EaseInCubic)
	mnu_move(CID, false, 0.1, 0, 14, EaseOutCubic)
	mnu_move(CID, false, 0.1, 0, -4, EaseInCubic)
	cmp_move(CID, 1.4, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_jump3",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4910,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4911,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-60",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4912,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "60",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4913,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-60",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4914,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "60",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4915,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-60",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4916,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "0",
	                "14",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4917,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "0",
	                "-4",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4918,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.4",
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
