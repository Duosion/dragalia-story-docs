.. _CHARA_BEAT3_AFTER:

CHARA_BEAT3_AFTER
========================

.. code-block:: text

	CHARA_BEAT3_AFTER(CID, CID2, CID3)


Arguments
------------

* CID
* CID2
* CID3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	WFOUT_SHORT()
	mnu(CID3, true, 0.6, 0, -150, EaseOutQuint, 0.6, 1, 1, 1, 0.6, 0, 1, 0.6, 0, 1)
	mnu(CID2, true, 0.6, 0, -150, EaseOutQuint, 0.6, 1, 1, 1, 0.6, 0, 1, 0.6, 0, 1)
	mnu(CID, true, 0.6, 0, -150, EaseOutQuint, 0.6, 1, 1, 1, 0.6, 0, 1, 0.6, 0, 1)
	wait(0.6)
	chara_visible(CID3, false)
	chara_face(CID3, 0)
	chara_visible(CID2, false)
	chara_face(CID2, 0)
	chara_visible(CID, false)
	chara_face(CID, 0)
	play_sound(SE_065)
	effect_shake_bg(12, 0.1, 0.2, 1)
	wait(0.5)
	RestartAll(CID)
	RestartAll(CID2)
	RestartAll(CID3)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`mnu`
* :ref:`wait`
* :ref:`chara_visible`
* :ref:`chara_face`
* :ref:`play_sound`
* :ref:`effect_shake_bg`
* :ref:`RestartAll`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_BEAT3_AFTER",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 4246,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4247,
	            "command": "mnu",
	            "args": [
	                "CID3",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint",
	                "0.6",
	                "1",
	                "1",
	                "1",
	                "0.6",
	                "0",
	                "1",
	                "0.6",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4248,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint",
	                "0.6",
	                "1",
	                "1",
	                "1",
	                "0.6",
	                "0",
	                "1",
	                "0.6",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4249,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.6",
	                "0",
	                "-150",
	                "EaseOutQuint",
	                "0.6",
	                "1",
	                "1",
	                "1",
	                "0.6",
	                "0",
	                "1",
	                "0.6",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4250,
	            "command": "wait",
	            "args": [
	                "0.6"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4251,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4252,
	            "command": "chara_face",
	            "args": [
	                "CID3",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4253,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4254,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4255,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4256,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4257,
	            "command": "play_sound",
	            "args": [
	                "SE_065"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4258,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.1",
	                "0.2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4259,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4260,
	            "command": "RestartAll",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4261,
	            "command": "RestartAll",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4262,
	            "command": "RestartAll",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
