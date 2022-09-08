.. _CHARA_SET_POS_0:

CHARA_SET_POS_0
========================

.. code-block:: text

	CHARA_SET_POS_0(eye, lip, X, Y, CID, int)


Arguments
------------

* eye
* lip
* X
* Y
* CID
* int

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	chara_visible(CID, false)
	chara_pos(CID, X, Y)
	chara_face(CID, int)
	eye1(CID, eye)
	lip1(CID, lip)

References
-------------
* :ref:`chara_visible`
* :ref:`chara_pos`
* :ref:`chara_face`
* :ref:`eye1`
* :ref:`lip1`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SET_POS_0",
	    "args": [
	        "eye",
	        "lip",
	        "X",
	        "Y",
	        "CID",
	        "int"
	    ],
	    "commandList": [
	        {
	            "row": 1817,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1818,
	            "command": "chara_pos",
	            "args": [
	                "CID",
	                "X",
	                "Y"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1819,
	            "command": "chara_face",
	            "args": [
	                "CID",
	                "int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1820,
	            "command": "eye1",
	            "args": [
	                "CID",
	                "eye"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1821,
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
