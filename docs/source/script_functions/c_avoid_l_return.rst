.. _c_avoid_l_return:

c_avoid_l_return
========================

.. code-block:: text

	c_avoid_l_return(CID)


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
	    "name": "c_avoid_l_return",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4706,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "200",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4707,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "200",
	                "50"
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
