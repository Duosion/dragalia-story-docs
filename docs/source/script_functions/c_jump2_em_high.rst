.. _c_jump2_em_high:

c_jump2_em_high
========================

.. code-block:: text

	c_jump2_em_high(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_jump2_em_high(CID):
		mnu_move(CID, true, 0.2, 0, 200, EaseOutCubic)
		mnu_move(CID, false, 0.2, 0, -210, EaseInCubic)
		mnu_move(CID, false, 0.2, 0, 150, EaseOutCubic)
		mnu_move(CID, false, 0.2, 0, -150, EaseInCubic)
		mnu_move(CID, false, 0.1, 0, 14, EaseOutCubic)
		mnu_move(CID, false, 0.1, 0, -4, EaseInCubic)
		cmp_move(CID, 1.0, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_jump2_em_high",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 206,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "200",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 207,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-210",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 208,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "150",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 209,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-150",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 210,
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
	            "row": 211,
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
	            "row": 212,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.0",
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
