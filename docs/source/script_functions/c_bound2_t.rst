.. _c_bound2_t:

c_bound2_t
========================

.. code-block:: text

	c_bound2_t(CID)


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
	    "name": "c_bound2_t",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4724,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.25",
	                "0",
	                "16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4725,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4726,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4727,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-16",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4728,
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
