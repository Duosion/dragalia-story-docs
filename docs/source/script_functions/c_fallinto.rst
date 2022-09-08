.. _c_fallinto:

c_fallinto
========================

.. code-block:: text

	c_fallinto(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.4, 0, -25, EaseOutCubic)
	mnu_move(CID, false, 0.1, 0, 0, 1)
	mnu_move(CID, false, 0.5, 16, 0, 9)
	mnu_move(CID, false, 0.5, -32, 0, 9)
	mnu_move(CID, false, 0.5, 16, 0, 9)
	cmp_move(CID, 2.0, 0, -25)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_fallinto",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4883,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.4",
	                "0",
	                "-25",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4884,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4885,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4886,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "-32",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4887,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "16",
	                "0",
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4888,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "2.0",
	                "0",
	                "-25"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
