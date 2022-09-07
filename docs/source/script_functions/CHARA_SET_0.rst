.. _CHARA_SET_0:

CHARA_SET_0
========================

.. code-block:: text

	CHARA_SET_0(eye, lip, POS, CID, int)


Arguments
------------

* eye
* lip
* POS
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SET_0",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1708,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1709,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "POS"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1710,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1711,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1712,
	            "command": "lip1",
	            "args": [
	                "CID",
	                "lip"
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
* :ref:`eye1`
* :ref:`lip1`
