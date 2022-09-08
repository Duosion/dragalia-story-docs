.. _event_still_move:

event_still_move
========================

.. code-block:: text

	event_still_move(Rayer, Sec, Rayer1, move1, Rayer2, move2, Rayer3, move3)


Arguments
------------

* Rayer
* Sec
* Rayer1
* move1
* Rayer2
* move2
* Rayer3
* move3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def event_still_move(Rayer, Sec, Rayer1, move1, Rayer2, move2, Rayer3, move3):
		if Rayer == "1":
			mnu_move(Rayer1, true, Sec, move1, 0, 1)
			cmp_move(Rayer1, Sec, move1, 0)
		elif Rayer == "2":
			mnu_move(Rayer1, true, Sec, move1, 0, 1)
			mnu_move(Rayer2, true, Sec, move2, 0, 1)
			cmp_move(Rayer1, Sec, move1, 0)
			cmp_move(Rayer2, Sec, move2, 0)
		elif Rayer == "3":
			mnu_move(Rayer1, true, Sec, move1, 0, 1)
			mnu_move(Rayer2, true, Sec, move2, 0, 1)
			mnu_move(Rayer3, true, Sec, move3, 0, 1)
			cmp_move(Rayer1, Sec, move1, 0)
			cmp_move(Rayer2, Sec, move2, 0)
			cmp_move(Rayer3, Sec, move3, 0)
		else:

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "event_still_move",
	    "args": [
	        "Rayer",
	        "Sec",
	        "Rayer1",
	        "move1",
	        "Rayer2",
	        "move2",
	        "Rayer3",
	        "move3"
	    ],
	    "commandList": [
	        {
	            "row": 5506,
	            "command": "if",
	            "args": [
	                "Rayer",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5507,
	            "command": "mnu_move",
	            "args": [
	                "Rayer1",
	                "true",
	                "Sec",
	                "move1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5508,
	            "command": "cmp_move",
	            "args": [
	                "Rayer1",
	                "Sec",
	                "move1",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5510,
	            "command": "elif",
	            "args": [
	                "Rayer",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5511,
	            "command": "mnu_move",
	            "args": [
	                "Rayer1",
	                "true",
	                "Sec",
	                "move1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5512,
	            "command": "mnu_move",
	            "args": [
	                "Rayer2",
	                "true",
	                "Sec",
	                "move2",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5513,
	            "command": "cmp_move",
	            "args": [
	                "Rayer1",
	                "Sec",
	                "move1",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5514,
	            "command": "cmp_move",
	            "args": [
	                "Rayer2",
	                "Sec",
	                "move2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5516,
	            "command": "elif",
	            "args": [
	                "Rayer",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5517,
	            "command": "mnu_move",
	            "args": [
	                "Rayer1",
	                "true",
	                "Sec",
	                "move1",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5518,
	            "command": "mnu_move",
	            "args": [
	                "Rayer2",
	                "true",
	                "Sec",
	                "move2",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5519,
	            "command": "mnu_move",
	            "args": [
	                "Rayer3",
	                "true",
	                "Sec",
	                "move3",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5520,
	            "command": "cmp_move",
	            "args": [
	                "Rayer1",
	                "Sec",
	                "move1",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5521,
	            "command": "cmp_move",
	            "args": [
	                "Rayer2",
	                "Sec",
	                "move2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5522,
	            "command": "cmp_move",
	            "args": [
	                "Rayer3",
	                "Sec",
	                "move3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5523,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5524,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
