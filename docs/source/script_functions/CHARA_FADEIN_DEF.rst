.. _CHARA_FADEIN_DEF:

CHARA_FADEIN_DEF
========================

.. code-block:: text

	CHARA_FADEIN_DEF(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	chara_fadein(CID, FIN_DEF)

References
-------------
* :ref:`chara_fadein`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_FADEIN_DEF",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 2473,
	            "command": "chara_fadein",
	            "args": [
	                "CID",
	                "FIN_DEF"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
