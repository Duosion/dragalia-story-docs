.. _CHARA_RESET:

CHARA_RESET
========================

.. code-block:: text

	CHARA_RESET(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_RESET(CID):
		chara_visible(CID, false)
		chara_face(CID, 0)
		RestartAll(CID)

References
-------------
* :ref:`chara_visible`
* :ref:`chara_face`
* :ref:`RestartAll`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_RESET",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2663,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2664,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2665,
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
