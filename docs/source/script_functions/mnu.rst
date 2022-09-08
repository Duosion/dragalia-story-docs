.. _mnu:

mnu
========================

.. code-block:: text

	mnu(CID, isNewAct, moveSec, moveX, moveY, moveEase, scaleSec, scaleX, scaleY, scaleEase, rotateSec, rotate, rotateEase, fadeSec, fade, fadeEase)


Arguments
------------

* CID
* isNewAct
* moveSec
* moveX
* moveY
* moveEase
* scaleSec
* scaleX
* scaleY
* scaleEase
* rotateSec
* rotate
* rotateEase
* fadeSec
* fade
* fadeEase

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def mnu(CID, isNewAct, moveSec, moveX, moveY, moveEase, scaleSec, scaleX, scaleY, scaleEase, rotateSec, rotate, rotateEase, fadeSec, fade, fadeEase):
		chara_act_manual(CID, isNewAct, moveSec, moveX, moveY, moveEase, scaleSec, scaleX, scaleY, scaleEase, rotateSec, rotate, rotateEase, fadeSec, fade, fadeEase)

References
-------------
* :ref:`chara_act_manual`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "mnu",
	    "args": [
	        "CID",
	        "isNewAct",
	        "moveSec",
	        "moveX",
	        "moveY",
	        "moveEase",
	        "scaleSec",
	        "scaleX",
	        "scaleY",
	        "scaleEase",
	        "rotateSec",
	        "rotate",
	        "rotateEase",
	        "fadeSec",
	        "fade",
	        "fadeEase"
	    ],
	    "commandList": [
	        {
	            "row": 4559,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "isNewAct",
	                "moveSec",
	                "moveX",
	                "moveY",
	                "moveEase",
	                "scaleSec",
	                "scaleX",
	                "scaleY",
	                "scaleEase",
	                "rotateSec",
	                "rotate",
	                "rotateEase",
	                "fadeSec",
	                "fade",
	                "fadeEase"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
