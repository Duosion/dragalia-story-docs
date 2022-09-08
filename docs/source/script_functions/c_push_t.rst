.. _c_push_t:

c_push_t
========================

.. code-block:: text

	c_push_t(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_push_t(CID):
		mnu_move(CID, true, 0.2, 0, 50, EaseOutCubic)
		cmp_move(CID, 0.2, 0, 50)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_push_t",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4601,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "50",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4602,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.2",
	                "0",
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
