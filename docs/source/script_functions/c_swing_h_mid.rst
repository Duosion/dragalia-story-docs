.. _c_swing_h_mid:

c_swing_h_mid
========================

.. code-block:: text

	c_swing_h_mid(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.08, 6, 0, 9)
	mnu_move(CID, false, 0.1, -12, 0, 9)
	mnu_move(CID, false, 0.08, 6, 0, 9)
	cmp_move(CID, 0.26, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_swing_h_mid",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4852,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.08",
	                "6",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4853,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "-12",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4854,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.08",
	                "6",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4855,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.26",
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
