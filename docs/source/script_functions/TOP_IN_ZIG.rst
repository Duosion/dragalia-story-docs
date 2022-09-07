.. _TOP_IN_ZIG:

TOP_IN_ZIG
========================

.. code-block:: text

	TOP_IN_ZIG(CID)


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
	    "name": "TOP_IN_ZIG",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2621,
	            "command": "c_zigzag_h_b",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2622,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.5"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`c_zigzag_h_b`
* :ref:`chara_fadein`
