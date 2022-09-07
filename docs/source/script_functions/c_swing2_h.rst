.. _c_swing2_h:

c_swing2_h
========================

.. code-block:: text

	c_swing2_h(CID)


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
	    "name": "c_swing2_h",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4803,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.25",
	                "16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4804,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "-32",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4805,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "32",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4806,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "-16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4807,
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

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
