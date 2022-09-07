.. _CHARA_BEAT_AFTER:

CHARA_BEAT_AFTER
========================

.. code-block:: text

	CHARA_BEAT_AFTER(CID)


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
	    "name": "CHARA_BEAT_AFTER",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4241,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 4242,
	            "command": "CHARA_BEAT_AFTER_0",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`WFOUT_SHORT`
* :ref:`CHARA_BEAT_AFTER_0`
