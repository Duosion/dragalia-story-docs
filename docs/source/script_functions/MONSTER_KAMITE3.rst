.. _MONSTER_KAMITE3:

MONSTER_KAMITE3
========================

.. code-block:: text

	MONSTER_KAMITE3(CID, CID2, CID3)


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
	    "name": "MONSTER_KAMITE3",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2343,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2344,
	            "command": "MONSTER_SET3_0",
	            "args": [
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2345,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2346,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2347,
	            "command": "KAMITE_IN_DEF",
	            "args": [
	                "CID3"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`MONSTER_SET3_0`
* :ref:`KAMITE_IN_DEF`
