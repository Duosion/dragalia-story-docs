.. _SHIMOTE_IN_ZIG:

SHIMOTE_IN_ZIG
========================

.. code-block:: text

	SHIMOTE_IN_ZIG(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SHIMOTE_IN_ZIG(CID):
		mnu_move(CID, true, 0.05, -160, 0, 1)
		mnu_move(CID, false, 0.15, 20, 20, 1)
		mnu_move(CID, false, 0.3, 40, -40, 1)
		mnu_move(CID, false, 0.3, 40, 40, 1)
		mnu_move(CID, false, 0.3, 40, -40, 1)
		mnu_move(CID, false, 0.15, 20, 20, 1)
		cmp_move(CID, 1.25, 0, 0)
		wait(0.05)
		chara_fadein(CID, 0.5)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
* :ref:`wait`
* :ref:`chara_fadein`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHIMOTE_IN_ZIG",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2604,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.05",
	                "-160",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2605,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.15",
	                "20",
	                "20",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2606,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "40",
	                "-40",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2607,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "40",
	                "40",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2608,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.3",
	                "40",
	                "-40",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2609,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.15",
	                "20",
	                "20",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2610,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.25",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2611,
	            "command": "wait",
	            "args": [
	                "0.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2612,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.5"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
