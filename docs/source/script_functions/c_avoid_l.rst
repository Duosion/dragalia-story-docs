.. _c_avoid_l:

c_avoid_l
========================

.. code-block:: text

	c_avoid_l(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_avoid_l(CID):
		mnu_move(CID, true, 0.3, -200, -50, EaseOutBack)
		cmp_move(CID, 0.3, -200, -50)
		wait(0.3)
		play_sound(SE_046)
		wait(0.1)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`
* :ref:`wait`
* :ref:`play_sound`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_avoid_l",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4698,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "-200",
	                "-50",
	                "EaseOutBack"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4699,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.3",
	                "-200",
	                "-50"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4700,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4701,
	            "command": "play_sound",
	            "args": [
	                "SE_046"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4702,
	            "command": "wait",
	            "args": [
	                "0.1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
