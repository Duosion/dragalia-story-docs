.. _mnu_fade:

mnu_fade
========================

.. code-block:: text

	mnu_fade(CID, isNewAct, fadeSec, fade, fadeEase)


Arguments
------------

* CID
* isNewAct
* fadeSec
* fade
* fadeEase

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def mnu_fade(CID, isNewAct, fadeSec, fade, fadeEase):
		chara_act_manual(CID, isNewAct, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, fadeSec, fade, fadeEase)

References
-------------
* :ref:`chara_act_manual`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "mnu_fade",
	    "args": [
	        "CID",
	        "isNewAct",
	        "fadeSec",
	        "fade",
	        "fadeEase"
	    ],
	    "commandList": [
	        {
	            "row": 4575,
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
	                "0",
	                "0",
	                "0",
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
