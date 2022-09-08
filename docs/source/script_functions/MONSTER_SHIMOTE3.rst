.. _MONSTER_SHIMOTE3:

MONSTER_SHIMOTE3
========================

.. code-block:: text

	MONSTER_SHIMOTE3(CID, CID2, CID3)


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

	WFOUT_DEF()
	MONSTER_SET3_0(CID, CID2, CID3)
	SHIMOTE_IN_DEF(CID)
	SHIMOTE_IN_DEF(CID2)
	SHIMOTE_IN_DEF(CID3)

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`MONSTER_SET3_0`
* :ref:`SHIMOTE_IN_DEF`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_SHIMOTE3",
	    "args": [
	        "CID",
	        "CID2",
	        "CID3"
	    ],
	    "commandList": [
	        {
	            "row": 2351,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2352,
	            "command": "MONSTER_SET3_0",
	            "args": [
	                "CID",
	                "CID2",
	                "CID3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2353,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2354,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2355,
	            "command": "SHIMOTE_IN_DEF",
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
