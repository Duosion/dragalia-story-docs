.. _c_jump_l:

c_jump_l
========================

.. code-block:: text

	c_jump_l(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.2, -50, 50, EaseOutCubic)
	mnu_move(CID, false, 0.2, -50, -60, EaseInCubic)
	mnu_move(CID, false, 0.1, 0, 14, EaseOutCubic)
	mnu_move(CID, false, 0.1, 0, -4, EaseInCubic)
	cmp_move(CID, 0.6, -100, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_jump_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4940,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "-50",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4941,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "-50",
	                "-60",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4942,
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
	            "row": 4943,
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
	            "row": 4944,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.6",
	                "-100",
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
