.. _c_avoid_r_return:

c_avoid_r_return
========================

.. code-block:: text

	c_avoid_r_return(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.3, -200, 50, EaseOutCubic)
	cmp_move(CID, 0.3, -200, 50)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_avoid_r_return",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4719,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-200",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4720,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "-200",
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
