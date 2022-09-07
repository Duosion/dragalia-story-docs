.. _MONSTER_SET3:

MONSTER_SET3
========================

.. code-block:: text

	MONSTER_SET3(CID, CID2, CID3)


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

.. code-block:: json

	{
	    "name": "MONSTER_SET3",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2332,
	            "command": "MONSTER_SET3_0",
	            "args": [
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2333,
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
	            "row": 2334,
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
	            "row": 2335,
	            "command": "mnu_fade",
	            "args": [
	                "CID3",
	                "true",
	                "0.3",
	                "1.0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2336,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2337,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2338,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2339,
	            "command": "chara_visible",
	            "args": [
	                "CID3",
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
* :ref:`MONSTER_SET3_0`
* :ref:`mnu_fade`
* :ref:`wait`
* :ref:`chara_visible`
