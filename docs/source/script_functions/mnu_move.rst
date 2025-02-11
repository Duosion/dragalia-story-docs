.. _mnu_move:

mnu_move
========================

.. code-block:: text

	mnu_move(CID, isNewAct, moveSec, moveX, moveY, moveEase)


Arguments
------------

* CID
* isNewAct
* moveSec
* moveX
* moveY
* moveEase

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def mnu_move(CID, isNewAct, moveSec, moveX, moveY, moveEase):
		chara_act_manual(CID, isNewAct, moveSec, moveX, moveY, moveEase)

References
-------------
* :ref:`chara_act_manual`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "mnu_move",
	    "args": [
	        "CID",
	        "isNewAct",
	        "moveSec",
	        "moveX",
	        "moveY",
	        "moveEase"
	    ],
	    "commandList": [
	        {
	            "row": 4563,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "isNewAct",
	                "moveSec",
	                "moveX",
	                "moveY",
	                "moveEase"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
