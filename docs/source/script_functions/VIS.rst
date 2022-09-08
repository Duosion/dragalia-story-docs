.. _VIS:

VIS
========================

.. code-block:: text

	VIS(CID, POS)


Arguments
------------

* CID
* POS

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	chara_visible(CID, false)
	chara_pos(CID, POS)

References
-------------
* :ref:`chara_visible`
* :ref:`chara_pos`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "VIS",
	    "args": [
	        "CID",
	        "POS"
	    ],
	    "commandList": [
	        {
	            "row": 1700,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1701,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "POS"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
