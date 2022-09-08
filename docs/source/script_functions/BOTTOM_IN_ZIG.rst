.. _BOTTOM_IN_ZIG:

BOTTOM_IN_ZIG
========================

.. code-block:: text

	BOTTOM_IN_ZIG(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def BOTTOM_IN_ZIG(CID):
		c_zigzag_h_t(CID)
		chara_fadein(CID, 0.5)

References
-------------
* :ref:`c_zigzag_h_t`
* :ref:`chara_fadein`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "BOTTOM_IN_ZIG",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2616,
	            "command": "c_zigzag_h_t",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2617,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "0.5"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
