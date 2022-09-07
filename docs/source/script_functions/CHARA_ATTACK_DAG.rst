.. _CHARA_ATTACK_DAG:

CHARA_ATTACK_DAG
========================

.. code-block:: text

	CHARA_ATTACK_DAG(CID)


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
	    "name": "CHARA_ATTACK_DAG",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3408,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3409,
	            "command": "play_sound",
	            "args": [
	                "SE_224"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3410,
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
	            "row": 3411,
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
	            "row": 3412,
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
