.. _CHANGE_DRAGON_RELEASE:

CHANGE_DRAGON_RELEASE
========================

.. code-block:: text

	CHANGE_DRAGON_RELEASE(CID, CID2, int)


Arguments
------------

* CID
* CID2
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	WFOUT_SHORT()
	set_BG_effect(EFF_020)
	play_sound(SE_005)
	wait(1.1)
	CHARA_RESET(CID)
	CHARA_SET(M, M, C, CID2, int)
	wait(0.5)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`set_BG_effect`
* :ref:`play_sound`
* :ref:`wait`
* :ref:`CHARA_RESET`
* :ref:`CHARA_SET`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHANGE_DRAGON_RELEASE",
	    "args": [
	        "CID",
	        "CID2",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 3098,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3099,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_020"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3100,
	            "command": "play_sound",
	            "args": [
	                "SE_005"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3101,
	            "command": "wait",
	            "args": [
	                "1.1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3102,
	            "command": "CHARA_RESET",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3103,
	            "command": "CHARA_SET",
	            "args": [
	                "M",
	                "M",
	                "C",
	                "CID2",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3104,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
