.. _c_swing_h:

c_swing_h
========================

.. code-block:: text

	c_swing_h(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_swing_h(CID):
		mnu_move(CID, true, 0.25, 16, 0, 9)
		mnu_move(CID, false, 0.25, -32, 0, 9)
		mnu_move(CID, false, 0.25, 16, 0, 9)
		cmp_move(CID, 0.75, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_swing_h",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4796,
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
	            "row": 4797,
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
	            "row": 4798,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.25",
	                "16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4799,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.75",
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
