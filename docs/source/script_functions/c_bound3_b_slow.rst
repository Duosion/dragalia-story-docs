.. _c_bound3_b_slow:

c_bound3_b_slow
========================

.. code-block:: text

	c_bound3_b_slow(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.5, 0, -12, EaseOutCubic)
	mnu_move(CID, false, 0.5, 0, 12, EaseOutCubic)
	mnu_move(CID, false, 0.5, 0, -12, EaseOutCubic)
	mnu_move(CID, false, 0.5, 0, 12, EaseOutCubic)
	mnu_move(CID, false, 0.5, 0, -12, EaseOutCubic)
	mnu_move(CID, false, 0.5, 0, 12, EaseOutCubic)
	cmp_move(CID, 3.0, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_bound3_b_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4770,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.5",
	                "0",
	                "-12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4771,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4772,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "-12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4773,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4774,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "-12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4775,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "12",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4776,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "3.0",
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
