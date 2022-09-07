.. _CHARA_ATTACK_KAT:

CHARA_ATTACK_KAT
========================

.. code-block:: text

	CHARA_ATTACK_KAT(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_ATTACK_KAT",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3400,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3401,
	            "command": "play_sound",
	            "args": [
	                "SE_225"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3402,
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
	            "row": 3403,
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
	            "row": 3404,
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

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`play_sound`
* :ref:`mnu_scale`
* :ref:`cmp_scale`
