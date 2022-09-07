.. _MONSTER_SET2:

MONSTER_SET2
========================

.. code-block:: text

	MONSTER_SET2(CID, CID2)


Arguments
------------

* CID
* CID2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_SET2",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 2125,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2126,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2127,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2128,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2129,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "12"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2130,
	            "command": "chara_face",
	            "args": [
	                "CID2",
	                "12"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2131,
	            "command": "mnu_fade",
	            "args": [
	                "CID",
	                "true",
	                "0.3",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2132,
	            "command": "mnu_fade",
	            "args": [
	                "CID2",
	                "true",
	                "0.3",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2133,
	            "command": "cmp_fade",
	            "args": [
	                "CID",
	                "0.3",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2134,
	            "command": "cmp_fade",
	            "args": [
	                "CID2",
	                "0.3",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2135,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2136,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "true"
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
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`chara_face`
* :ref:`mnu_fade`
* :ref:`cmp_fade`
