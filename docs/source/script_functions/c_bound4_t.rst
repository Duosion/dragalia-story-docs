.. _c_bound4_t:

c_bound4_t
========================

.. code-block:: text

	c_bound4_t(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_bound4_t(CID):
		mnu_move(CID, true, 0.25, 0, 16, EaseOutCubic)
		mnu_move(CID, false, 0.25, 0, -16, EaseOutCubic)
		mnu_move(CID, false, 0.25, 0, 24, EaseOutCubic)
		mnu_move(CID, false, 0.25, 0, -24, EaseOutCubic)
		mnu_move(CID, false, 0.25, 0, 32, EaseOutCubic)
		mnu_move(CID, false, 0.25, 0, -32, EaseOutCubic)
		mnu_move(CID, false, 0.25, 0, 16, EaseOutCubic)
		mnu_move(CID, false, 0.25, 0, -16, EaseOutCubic)
		cmp_move(CID, 2.0, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_bound4_t",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4742,
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
	            "row": 4743,
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
	            "row": 4744,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "24",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4745,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-24",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4746,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "32",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4747,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "0",
	                "-32",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4748,
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
	            "row": 4749,
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
	            "row": 4750,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "2.0",
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
