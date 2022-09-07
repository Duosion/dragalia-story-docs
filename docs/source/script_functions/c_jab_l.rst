.. _c_jab_l:

c_jab_l
========================

.. code-block:: text

	c_jab_l(CID)


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
	    "name": "c_jab_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4962,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.15",
	                "-80",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4963,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "80",
	                "0",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4964,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.25",
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
