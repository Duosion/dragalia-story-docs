.. _cmp:

cmp
========================

.. code-block:: text

	cmp(CID, sec, moveX, moveY, scaleX, scaleY, rotate, fade)


Arguments
------------

* CID
* sec
* moveX
* moveY
* scaleX
* scaleY
* rotate
* fade

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "cmp",
	    "args": [
	        "CID",
	        "sec",
	        "moveX",
	        "moveY",
	        "scaleX",
	        "scaleY",
	        "rotate",
	        "fade"
	    ],
	    "commandList": [
	        {
	            "row": 4578,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "sec",
	                "moveX",
	                "moveY",
	                "scaleX",
	                "scaleY",
	                "rotate",
	                "fade"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}

References
-------------
* :ref:`chara_act_complete`
