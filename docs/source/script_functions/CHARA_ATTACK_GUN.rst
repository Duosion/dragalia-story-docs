.. _CHARA_ATTACK_GUN:

CHARA_ATTACK_GUN
========================

.. code-block:: text

	CHARA_ATTACK_GUN(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_ATTACK_GUN(CID):
		WFOUT_SHORT()
		mnu_scale(CID, true, 0.15, 1.35, 1.35, EaseOutCubic)
		mnu_scale(CID, false, 0.15, 1, 1, EaseOutCubic)
		cmp_scale(CID, 0.3, 1, 1)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`mnu_scale`
* :ref:`cmp_scale`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_ATTACK_GUN",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3440,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3442,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "true",
	                "0.15",
	                "1.35",
	                "1.35",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3443,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "false",
	                "0.15",
	                "1",
	                "1",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3444,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.3",
	                "1",
	                "1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
