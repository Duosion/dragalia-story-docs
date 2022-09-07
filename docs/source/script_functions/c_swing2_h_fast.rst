.. _c_swing2_h_fast:

c_swing2_h_fast
========================

.. code-block:: text

	c_swing2_h_fast(CID)


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
	    "name": "c_swing2_h_fast",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4866,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.08",
	                "10",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4867,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "-20",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4868,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "20",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4869,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "-20",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4870,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "10",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4871,
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
