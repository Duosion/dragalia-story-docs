.. _c_jump2_em:

c_jump2_em
========================

.. code-block:: text

	c_jump2_em(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.2, 0, 100, EaseOutCubic)
	mnu_move(CID, false, 0.2, 0, -110, EaseInCubic)
	mnu_move(CID, false, 0.2, 0, 60, EaseOutCubic)
	mnu_move(CID, false, 0.2, 0, -60, EaseInCubic)
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
	    "name": "c_jump2_em",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4930,
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
	            "row": 4931,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "0",
	                "-110",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4932,
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
	            "row": 4933,
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
	            "row": 4934,
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
	            "row": 4935,
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
	            "row": 4936,
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
