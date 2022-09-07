.. _mnu_scale:

mnu_scale
========================

.. code-block:: text

	mnu_scale(CID, isNewAct, scaleSec, scaleX, scaleY, scaleEase)


Arguments
------------

* CID
* isNewAct
* scaleSec
* scaleX
* scaleY
* scaleEase

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "mnu_scale",
	    "args": [
	        "CID",
	        "isNewAct",
	        "scaleSec",
	        "scaleX",
	        "scaleY",
	        "scaleEase"
	    ],
	    "commandList": [
	        {
	            "row": 4567,
	            "command": "chara_act_manual",
	            "args": [
	                "CID",
	                "isNewAct",
	                "0",
	                "0",
	                "0",
	                "0",
	                "scaleSec",
	                "scaleX",
	                "scaleY",
	                "scaleEase"
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
* :ref:`chara_act_manual`
