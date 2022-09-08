.. _c_jump_em:

c_jump_em
========================

.. code-block:: text

	c_jump_em(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_jump_em(CID):
		mnu_move(CID, true, 0.2, 0, 100, EaseOutCubic)
		mnu_move(CID, false, 0.25, 0, -110, EaseInCubic)
		mnu_move(CID, false, 0.1, 0, 14, EaseOutCubic)
		mnu_move(CID, false, 0.1, 0, -4, EaseInCubic)
		cmp_move(CID, 0.65, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_jump_em",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4922,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "100",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4923,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-110",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4924,
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
	            "row": 4925,
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
	            "row": 4926,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.65",
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
