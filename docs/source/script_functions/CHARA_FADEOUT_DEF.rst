.. _CHARA_FADEOUT_DEF:

CHARA_FADEOUT_DEF
========================

.. code-block:: text

	CHARA_FADEOUT_DEF(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	NO_EMO(CID)
	RESET_TEXT()
	chara_fadeout(CID, 0.2)
	RestartAll(CID)

References
-------------
* :ref:`NO_EMO`
* :ref:`RESET_TEXT`
* :ref:`chara_fadeout`
* :ref:`RestartAll`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_FADEOUT_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2628,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2629,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 2630,
	            "command": "chara_fadeout",
	            "args": [
	                "CID",
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2631,
	            "command": "RestartAll",
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
