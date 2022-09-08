.. _c_push_r:

c_push_r
========================

.. code-block:: text

	c_push_r(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_push_r(CID):
		mnu_move(CID, true, 0.2, 50, 0, EaseOutCubic)
		cmp_move(CID, 0.2, 50, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_push_r",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4650,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "50",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4651,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.2",
	                "50",
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
