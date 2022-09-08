.. _CHARA_ATTACK_SWD:

CHARA_ATTACK_SWD
========================

.. code-block:: text

	CHARA_ATTACK_SWD(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	WFOUT_SHORT()
	play_sound(SE_228)
	mnu_scale(CID, true, 0.15, 1.35, 1.35, EaseOutCubic)
	mnu_scale(CID, false, 0.15, 1, 1, EaseOutCubic)
	cmp_scale(CID, 0.3, 1, 1)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`play_sound`
* :ref:`mnu_scale`
* :ref:`cmp_scale`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_ATTACK_SWD",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 3392,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3393,
	            "command": "play_sound",
	            "args": [
	                "SE_228"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3394,
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
	            "row": 3395,
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
	            "row": 3396,
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
