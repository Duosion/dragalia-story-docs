.. _c_push2_l:

c_push2_l
========================

.. code-block:: text

	c_push2_l(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_push2_l(CID):
		mnu_move(CID, true, 0.3, -50, 0, EaseOutCubic)
		mnu_move(CID, false, 0.5, 0, 0, EaseOutCubic)
		mnu_move(CID, false, 0.2, -30, 0, EaseOutCubic)
		cmp_move(CID, 1.0, -80, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_push2_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4626,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-50",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4627,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4628,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "-30",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4629,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.0",
	                "-80",
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
