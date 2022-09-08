.. _mnu_rotate:

mnu_rotate
========================

.. code-block:: text

	mnu_rotate(CID, isNewAct, rotateSec, rotate, rotateEase)


Arguments
------------

* CID
* isNewAct
* rotateSec
* rotate
* rotateEase

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def mnu_rotate(CID, isNewAct, rotateSec, rotate, rotateEase):
		chara_act_manual(CID, isNewAct, 0, 0, 0, 0, 0, 0, 0, 0, rotateSec, rotate, rotateEase)

References
-------------
* :ref:`chara_act_manual`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "mnu_rotate",
	    "args": [
	        "CID",
	        "isNewAct",
	        "rotateSec",
	        "rotate",
	        "rotateEase"
	    ],
	    "commandList": [
	        {
	            "row": 4571,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "isNewAct",
	                "0",
	                "0",
	                "0",
	                "0",
	                "0",
	                "0",
	                "0",
	                "0",
	                "rotateSec",
	                "rotate",
	                "rotateEase"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
