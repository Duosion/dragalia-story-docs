.. _cmp_move:

cmp_move
========================

.. code-block:: text

	cmp_move(CID, sec, moveX, moveY)


Arguments
------------

* CID
* sec
* moveX
* moveY

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	chara_act_complete(CID, sec, moveX, moveY)

References
-------------
* :ref:`chara_act_complete`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "cmp_move",
	    "args": [
	        "CID",
	        "sec",
	        "moveX",
	        "moveY"
	    ],
	    "commandList": [
	        {
	            "row": 4582,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "sec",
	                "moveX",
	                "moveY"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
