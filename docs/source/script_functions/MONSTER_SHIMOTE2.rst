.. _MONSTER_SHIMOTE2:

MONSTER_SHIMOTE2
========================

.. code-block:: text

	MONSTER_SHIMOTE2(CID, CID2)


Arguments
------------

* CID
* CID2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_SHIMOTE2(CID, CID2):
		WFOUT_DEF()
		chara_visible(CID, false)
		chara_visible(CID2, false)
		chara_pos(CID, 3)
		chara_pos(CID2, 1)
		SHIMOTE_IN_DEF(CID)
		wait(0.3)
		SHIMOTE_IN_DEF(CID2)

References
-------------
* :ref:`WFOUT_DEF`
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`SHIMOTE_IN_DEF`
* :ref:`wait`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_SHIMOTE2",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 2140,
	            "command": "WFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2141,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2142,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2143,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2144,
	            "command": "chara_pos",
	            "args": [
	                "CID2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2145,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2146,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2147,
	            "command": "SHIMOTE_IN_DEF",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
