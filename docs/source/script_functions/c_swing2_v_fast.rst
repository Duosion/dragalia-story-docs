.. _c_swing2_v_fast:

c_swing2_v_fast
========================

.. code-block:: text

	c_swing2_v_fast(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "c_swing2_v_fast",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4875,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.08",
	                "0",
	                "10",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4876,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "0",
	                "-20",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4877,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "0",
	                "20",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4878,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "0",
	                "-20",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4879,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "0",
	                "10",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4880,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.4",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
