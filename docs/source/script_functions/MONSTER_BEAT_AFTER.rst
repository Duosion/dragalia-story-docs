.. _MONSTER_BEAT_AFTER:

MONSTER_BEAT_AFTER
========================

.. code-block:: text

	MONSTER_BEAT_AFTER(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def MONSTER_BEAT_AFTER(CID):
		WFOUT_SHORT()
		MONSTER_BEAT_AFTER_0(CID)

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`MONSTER_BEAT_AFTER_0`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "MONSTER_BEAT_AFTER",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4205,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4206,
	            "command": "MONSTER_BEAT_AFTER_0",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
